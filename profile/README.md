<div align="center">

<a href="https://oxylabs.io">
  <img src="https://raw.githubusercontent.com/oxylabs/.github/main/profile/oxylabs-logo.png" alt="Oxylabs Logo" width="200">
</a>

# Oxylabs

Welcome to Oxylabs on GitHub.
#### Fresh web data for grounding AI agents, and for every team that depends on real-time public data.
Whether you're doing web scraping at scale, routing traffic through proxies, or giving an AI agent a window onto the live web, you're in the right place.

<a href="https://oxylabs.io"><img src="https://img.shields.io/badge/🚀_Get_Started-FF6B35?style=for-the-badge" alt="Get started"></a>
<a href="https://developers.oxylabs.io"><img src="https://img.shields.io/badge/📚_Documentation-4A90E2?style=for-the-badge" alt="Documentation"></a>
<a href="https://dashboard.oxylabs.io"><img src="https://img.shields.io/badge/📊_Dashboard-2EA44F?style=for-the-badge" alt="Dashboard"></a>
<a href="https://discord.gg/YOUR-INVITE"><img src="https://img.shields.io/badge/💬_Discord-5865F2?style=for-the-badge" alt="Discord"></a>
<a href="https://www.youtube.com/@oxylabs"><img src="https://img.shields.io/badge/▶️_YouTube-FF0000?style=for-the-badge" alt="YouTube"></a>

</div>

---

## About Oxylabs

Oxylabs turns the public web into data that your business and your AI agents can put to work. We provide the tools and infrastructure for accessing publicly available web data, and we take care of the hard parts of large-scale web access: network routing, access reliability, and resilience to access interruptions.

Public web data powers price tracking, content monitoring, analytics, and AI. Getting it is harder than it looks: every request has to reach the right site from the right place, come back complete, and keep working as you scale up.

Oxylabs gives you the tools and infrastructure to do that. You choose how much help you want:

| If you say... | Oxylabs gives you... |
| --- | --- |
| *"My app or AI agent needs to search the live web and read pages."* | The newest Oxylabs product, one REST API with two endpoints [Web API](https://oxylabs.io/products/web-api/). |
| *"I already have a scraper. I need the roads to the web."* | A large network of IP addresses to route your own requests through [Proxies](https://oxylabs.io/products). |
| *"My pipeline keeps getting stopped."* | An AI-powered proxy solution that manages the hard parts for you [Web Unblocker](https://oxylabs.io/products/web-unblocker). |
| *"I need a real browser, or my AI agent does."* | A cloud-based browser you control remotely [Agent Browser](https://oxylabs.io/products/agent-browser). |
| *"I'm building with an AI coding assistant."* | Official [Agent Skills](https://developers.oxylabs.io/ai-workflows/agent-skills) and an [MCP server](https://developers.oxylabs.io/ai-workflows/mcp). |
| *"Just give me the data."* | An all-in-one, fully managed data collection service [Web Scraper API](https://developers.oxylabs.io/products/web-scraper-api). |

## Built for you

- Developers building data-driven software
- Data teams gathering web data at scale
- AI teams requiring real-time public data from the web
- Companies that depend on unrestricted web access

## What Oxylabs does

### Web API

An all-in-one REST API for web search and page data collection. The Oxylabs [Web API](https://oxylabs.io/products/web-api) gives applications and AI agents live access to the open web through a unified REST interface.

Finding the right, fresh pages is one problem. Reading them reliably is another. Web API handles both. It takes care of JavaScript rendering, bot traffic challenges, proxy rotation, and geo-targeting, and exposes separate endpoints for the different stages of web data acquisition:

| Endpoint | What it does | You send |
| --- | --- | --- |
| `/search` | Discovers and ranks organic web results from the live web | A keyword or query |
| `/scrape` | Renders a page and extracts its data as Markdown, HTML, JSON, or a screenshot | A page URL |

**What's inside:**

- **Multiple output formats.** Request Markdown, HTML, JSON, or a screenshot, and more than one in a single request.
- **Dedicated scrapers.** Target-specific endpoints with structured field extraction, covering search engines (Google, Bing), commerce sites (Amazon, Walmart, Target, and more), media (YouTube), and AI platforms (ChatGPT, Gemini, Perplexity).
- **AI Parsing.** Extract structured JSON from any page in one request, using a natural-language prompt or a JSON Schema.
- **Flexible delivery.** Real-time responses, async jobs with polling or callbacks, cloud storage delivery, and batch requests.
- **Endpoint Discovery.** List all up-to-date scrape endpoints and their parameters at runtime instead of hardcoding them.
- **Playground.** Build and test Search and Scrape requests, preview results, and export ready-to-use code.
- **Built for AI agents.** Connect it with Agent Skills, an MCP server, or a one-prompt integration. See Agent Skills and MCP server.

Pick it when you want to give an AI agent live web search and structured data, without managing proxies. Web API is billed per result or search.

### Proxies, including Residential Proxies

Route your own requests through 177+ million IPs in 195 countries. Oxylabs Residential Proxies use real IP addresses provided by Internet Service Providers (ISPs) attached to physical devices globally. They rotate automatically with every request and support country, city, state, ZIP code, ASN, and session targeting.

| Proxy type | In plain English | Pick it when you want to... |
| --- | --- | --- |
| [Residential Proxies](https://oxylabs.io/products/residential-proxy-pool) | Real ISP-provided IPs from around the world, rotating or sticky | Run your own scraper through residential IPs with precise geo-targeting |
| [Mobile Proxies](https://oxylabs.io/products/mobile-proxies) | IPs from real mobile devices, 140+ locations | See what a mobile user sees |
| [ISP Proxies](https://oxylabs.io/products/isp-proxies) and [Dedicated ISP Proxies](https://oxylabs.io/products/dedicated-isp-proxies) | Static IPs from premium ASN providers. With Dedicated ISP Proxies the IPs are private and you choose the ASN | Keep stable sessions on demanding targets |
| [Datacenter Proxies](https://oxylabs.io/products/datacenter-proxies) | Fast, cost-effective IPs. Dedicated ones are not shared with anyone else | Scrape at high volume where speed and price matter most |
| [High-Bandwidth Proxies](https://oxylabs.io/products/high-bandwidth-proxies) | Proxies for traffic-intensive tasks | Handle jobs such as video and audio scraping |

Repository: [oxylabs/residential-proxies](https://github.com/oxylabs/residential-proxies) · Free to try: [oxylabs/free-proxy-list](https://github.com/oxylabs/free-proxy-list)

### Agent Browser

[Agent Browser](https://oxylabs.io/products/agent-browser) is a cloud-based headless browser with built-in adaptive security, CAPTCHA management, and residential proxies. Run and control remote browser instances for automation, testing, and web scraping without managing them locally. Connect with Playwright, Puppeteer, or any Chrome DevTools Protocol (CDP) library, including AI agent frameworks such as Stagehand and browser-use.

Repository: [oxylabs/agent-browser](https://github.com/oxylabs/agent-browser) · Docs: [Agent Browser](https://developers.oxylabs.io)

### Web Unblocker

Oxylabs' [Web Unblocker](https://oxylabs.io/products/web-unblocker) is an AI-powered proxy solution that manages the request process so you can extract public data even from the most difficult websites. It is not a regular proxy: it manages proxy type selection, browser fingerprint generation, retries, sessions, and JavaScript rendering for you. Oxylabs documentation describes it as delivering a much higher success rate than regular proxies.

Repository: [oxylabs/web-unblocker](https://github.com/oxylabs/web-unblocker) · Docs: [Web Unblocker](https://developers.oxylabs.io)

### Web Scraper API (Classic)

Retrieve web pages through an all-in-one, fully managed data collection infrastructure. Send a request, get your data back. For supported websites such as Amazon and Google, the API can return structured JSON instead of raw HTML.

Repository: [oxylabs/web-scraper-api](https://github.com/oxylabs/web-scraper-api) · Docs: [Web Scraper API](https://developers.oxylabs.io)

### Agent Skills and MCP server

Official Agent Skills teach AI coding assistants how to configure and use Oxylabs products accurately. 
MCP servers give MCP-compatible assistants tools they can call directly: live web search and scraping through Web API, scraping of any URL, Google Search, and Amazon through Web Scraper API, and a remote Agent Browser they can drive.

Repositories: [oxylabs/web-api-skills](https://github.com/oxylabs/web-api-skills) · [oxylabs/agent-skills](https://github.com/oxylabs/agent-skills) · [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) · [oxylabs/oxylabs-ab-mcp](https://github.com/oxylabs/oxylabs-ab-mcp)

## Which product should you use?

Start with your goal. This table follows the guidance in the Oxylabs [help center](https://developers.oxylabs.io/help-center/most-popular-questions/how-do-i-choose-the-right-product).

| If you want to... | Choose |
| --- | --- |
| Give an AI agent live web search and structured data, without managing proxies | [Web API](https://developers.oxylabs.io/products/web-api) (`/search` and `/scrape` endpoints) |
| Run your own scraper through residential IPs with precise geo-targeting | [Residential Proxies](https://developers.oxylabs.io/products/proxies/residential-proxies) |
| See what a mobile user sees | [Mobile Proxies](https://developers.oxylabs.io/products/proxies/mobile-proxies) |
| Keep stable sessions on demanding targets | [ISP Proxies](https://developers.oxylabs.io/products/proxies/isp-proxies) or [Dedicated ISP Proxies](https://developers.oxylabs.io/products/proxies/dedicated-isp-proxies) |
| Scrape at high volume where speed and price matter most | [Datacenter Proxies](https://developers.oxylabs.io/products/proxies/datacenter-proxies) or [Dedicated Datacenter Proxies](https://developers.oxylabs.io/products/proxies/dedicated-datacenter-proxies) |
| Automate a browser, or give an AI agent one | [Agent Browser](https://developers.oxylabs.io/products/agent-browser) |
| Get reliable access to complex sites with automated request management | [Web Unblocker](https://developers.oxylabs.io/products/web-unblocker) |
| Retrieve web pages through a fully managed, all-in-one service | [Web Scraper API (Classic)](https://developers.oxylabs.io/products/web-scraper-api) |


> [!Tip]
> **Not sure yet?**
> Test first in our [Dashboard](https://dashboard.oxylabs.io/en/registration). Every new account gets a $5 welcome credit that works on any product.


## How Oxylabs is different

Large-scale web access comes down to a few hard problems. Here is how each Oxylabs product family approaches them.

| The challenge | How Oxylabs approaches it |
| --- | --- |
| **Finding and reading the live web** | Web API separates the stages: `/search` discovers and ranks results, `/scrape` renders and extracts pages, with rendering, proxy rotation, and geo-targeting handled for you |
| **Network routing:** reaching sites from the right place | A proxy network of 177+ million IPs in 195 countries, in residential, mobile, ISP, and datacenter flavors, with targeting down to country, city, state, ZIP code, ASN, and coordinates |
| **Access reliability:** getting a good response consistently | Web Unblocker manages proxy type, browser fingerprints, retries, sessions, and JavaScript rendering for you |
| **Flagging resistance:** pages that fight automation | Agent Browser combines adaptive security, CAPTCHA management, and residential proxies in one remote browser |
| **Fitting into AI workflows** | Official Agent Skills and an MCP server ship alongside the products |

**What sets the platform apart**

- **You choose your level of control.** Use your own tools powered by the Oxylabs proxy network, or use the all-in-one API and start scraping right away without building your own infrastructure.
- **One credit balance across every product.** Usage from all products comes out of the same balance. You can try more than one product before you commit, and you can set a spending limit per product instance.
- **Built to work with AI assistants.** With an Agent Skill installed, your assistant writes accurate connection strings, request payloads, and automation code without syntax or parameter hallucinations.
- **Integration guides** for the tools you already use, from Playwright, Puppeteer, Scrapy, and Selenium to LangChain, LlamaIndex, and Postman.

## Why choose Oxylabs?

- **A new way to give agents the live web.** The Web API pairs `/search` and `/scrape` in one REST interface, with Markdown, HTML, JSON, or screenshot output and AI Parsing for structured data.
- **Global coverage.** 177+ million IPs in 195 countries, with granular geo-targeting.
- **The right tool for the job.** Residential, mobile, ISP, and datacenter proxies, plus managed products (Web API, Web Unblocker, Agent Browser, Web Scraper API) when you would rather not run the plumbing yourself.
- **AI-ready.** Agent Skills, MCP servers, and LangChain and LlamaIndex integrations.
- **Easy to try.** A $5 welcome credit, a shared credit balance, and quick-start guides that get you to a first request in minutes.
- **Security and compliance you can point to.** Our information security management system is certified to ISO/IEC 27001:2022 (for the scope set out in our Trust Center), and Web Unblocker has completed an independent SOC 2 Type 2 audit. See [Trust and responsible use](https://claude.ai/chat/2adf7d51-6b56-4142-b92e-479dae35eba9#trust-and-responsible-use).
- **Help when you need it.** A 24/7 support team through live chat or email, a Dedicated Account Manager for enterprise customers, and an AI assistant built into the documentation search.

## Core ecosystem

Everything you need, in one place. Start with the repository that matches your goal.

| Repository | What it is | Best for |
| --- | --- | --- |
| [web-api](https://oxylabs.io/products/web-api) | One REST API with `/search` and `/scrape` endpoints for live web access | Giving applications and AI agents live search and page reading |
| [agent-skills](https://github.com/oxylabs/agent-skills) | Official Agent Skills for Oxylabs products: `proxies`, `agent-browser`, `web-unblocker`, `video-data`, and `web-scraper-api` | Teaching Claude Code, Cursor, and other AI coding assistants to use Oxylabs correctly |
| [agent-browser](https://github.com/oxylabs/agent-browser) | Overview and guide for Agent Browser: remote cloud browser sessions with integrated residential proxies, CAPTCHA handling, and JavaScript rendering | Browser automation, testing, and AI agents that need a real browser |
| [oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp) | MCP server for Web Scraper API, also hosted at `mcp.oxylabs.io` | Letting assistants scrape any URL, Google Search, and Amazon |
| [oxylabs-ab-mcp](https://github.com/oxylabs/oxylabs-ab-mcp) | MCP server for Agent Browser | Giving MCP-compatible assistants a remote browser |
| [residential-proxies](https://github.com/oxylabs/residential-proxies) | Rotating Residential Proxies: code examples and general information | Running your own scraper through residential IPs |
| [web-unblocker](https://github.com/oxylabs/web-unblocker) | Web Unblocker repository | Reaching difficult sites without managing the details |
| [web-scraper-api](https://github.com/oxylabs/web-scraper-api) | Overview and guide for Web Scraper API | Fully managed, all-in-one data collection |

## Common use cases

Across products, people use Oxylabs for:

- Collecting public listings and prices
- Monitoring online content
- Building datasets for analytics
- Powering data-driven applications and AI

And by need:

| I want to... | Start with |
| --- | --- |
| Give an AI assistant a remote browser to navigate pages, click, fill forms, and take screenshots | [Agent Browser](https://developers.oxylabs.io/products/agent-browser) with the [MCP server](https://github.com/oxylabs/oxylabs-ab-mcp) |
| Have my AI coding assistant write correct Oxylabs code | [Agent Skills](https://github.com/oxylabs/agent-skills) |
| Automate or test a website with Playwright or Puppeteer | [Agent Browser](https://developers.oxylabs.io/products/agent-browser) |
| View a site as a visitor from a specific country, city, or ZIP code would | [Residential Proxies](https://developers.oxylabs.io/products/proxies/residential-proxies) |
| Reach a site that keeps interrupting my existing scraper | [Web Unblocker](https://developers.oxylabs.io/products/web-unblocker) |
| Collect YouTube metadata, subtitles, search results, or channel data, or download video and audio | The `video-data` skill in [Agent Skills](https://github.com/oxylabs/agent-skills) |
| Connect Oxylabs to LLM workflows | [LangChain](https://developers.oxylabs.io/ai-workflows/langchain) and [LlamaIndex](https://developers.oxylabs.io/ai-workflows/llamaindex) integrations |
| Get structured data from supported targets without building a parser | [Web Scraper API](https://developers.oxylabs.io/products/web-scraper-api) |

## Getting started

Every product follows the same three-step pattern:

1. **Get access.** Create an account in the [dashboard](https://dashboard.oxylabs.io/), choose a product, and select Create instance. Your username and password are generated as soon as you confirm.
2. **Connect.** Add the product's endpoint to your code or tool. Residential Proxies have an Endpoint Generator, Web Unblocker has a single endpoint, and Agent Browser works with Puppeteer, Playwright, CDP, and MCP clients.
3. **Send your first request.** Run your script and get your data back.

You can optionally cap spending per instance at creation. A new account includes a $5 welcome credit that works on any product.

**Quick-start guides:**

- [Web API](https://developers.oxylabs.io/get-started/quick-start-web-api)
- [Proxies](https://developers.oxylabs.io/get-started/quick-start-proxies)
- [Web Unblocker](https://developers.oxylabs.io/get-started/quick-start-web-unblocker)
- [Agent Browser](https://developers.oxylabs.io/get-started/quick-start-agent-browser)

Prefer to let your AI assistant handle setup? Install [Agent Skills](https://developers.oxylabs.io/ai-workflows/agent-skills).

## Integrations

Our step-by-step [integration guides](https://developers.oxylabs.io/integrations) cover third-party tools including Playwright, Puppeteer, Scrapy, Selenium, and Postman, plus browser and multi-login tools for proxies.

## Agent Skills and MCP server for AI workflows

Two complementary ways to bring Oxylabs into AI assistants and agents:

| | Agent Skills | MCP server |
| --- | --- | --- |
| **Gives the assistant** | Knowledge: how to write correct code and configuration for Oxylabs products | Tools: a remote browser it can call directly |
| **Needs a running process** | No | Yes |
| **Works in** | Agents that load skill directories | Any MCP client |

Skills teach your assistant how to write code for Oxylabs products. The MCP server lets your assistant act directly. Using both together is a common setup.

### Agent Skills

One repository, [oxylabs/agent-skills](https://github.com/oxylabs/agent-skills), covers five skills:

| Skill | What it helps your assistant do |
| --- | --- |
| [`proxies`](https://github.com/oxylabs/agent-skills/blob/main/skills/proxies/SKILL.md) | Generate connection strings, handle entry nodes, and apply geo-targeting, IP rotation, and session persistence |
| [`agent-browser`](https://github.com/oxylabs/agent-skills/blob/main/skills/agent-browser/SKILL.md) | Control remote browsers via CDP, configure fingerprints, and manage Playwright or Puppeteer automation |
| [`web-unblocker`](https://github.com/oxylabs/agent-skills/blob/main/skills/web-unblocker/SKILL.md) | Route traffic through the correct gateways, manage custom headers, toggle JavaScript rendering, and configure SSL |
| [`video-data`](https://github.com/oxylabs/agent-skills/blob/main/skills/video-data/SKILL.md) | Extract video metadata, subtitles, search results, and channel data, and download video or audio via High-Bandwidth Proxies |
| [`web-scraper-api`](https://github.com/oxylabs/agent-skills/blob/main/skills/web-scraper-api/SKILL.md) | Build request payloads, custom parsing parameters, and geo-targeting fields, and format JSON output |

Setup for Claude Desktop and Cursor, the full tool list, and troubleshooting: [Agent Skills docs](https://developers.oxylabs.io/ai-workflows/agent-skills).

### MCP server

Each product has its own MCP server and its own credentials. Set up only the ones you need, or combine them in one client.

| Product | MCP server | Setup |
| --- | --- | --- |
| Web API | `oxylabs-web-api-mcp` | Self-hosted, local or HTTP (see Web API for AI agents above) |
| Web Scraper API | Oxylabs MCP server, hosted at `mcp.oxylabs.io` | Hosted |
| Agent Browser | `hb-mcp` | Local |

Setup for Claude Desktop and Cursor, the full tool list, and troubleshooting: [MCP docs](https://developers.oxylabs.io/ai-workflows/mcp).

### More AI integrations

[LangChain](https://developers.oxylabs.io/ai-workflows/langchain) and [LlamaIndex](https://developers.oxylabs.io/ai-workflows/llamaindex) integrations work with the Web Scraper API to pull web data into LLM workflows.

## Custom and open-source solutions

Beyond the core products, Oxylabs maintains open-source repositories with ready-to-use scrapers, tutorials, and examples. Fork them, learn from them, or use them as a starting point.

| Repository | What you'll find |
| --- | --- |
| [web-scraping-tutorials](https://github.com/oxylabs/web-scraping-tutorials) | Web scraping, data parsing, and automation tutorials for beginners through advanced programmers |
| [amazon-scraper](https://github.com/oxylabs/amazon-scraper) | Amazon scraper for search, product, offer listing, reviews, questions and answers, best sellers, and sellers data |
| [google-news-scraper](https://github.com/oxylabs/google-news-scraper) | Google News scraper for headlines, sources, URLs, and publication dates |
| [google-ai-mode-scraper](https://github.com/oxylabs/google-ai-mode-scraper) | Scrape Google AI Mode responses at scale |
| [masque-http3-go-example](https://github.com/oxylabs/masque-http3-go-example) | Go example of MASQUE, the IETF-standardized framework for proxying traffic over HTTP/3 or HTTP/2 |
| [LLM-Fine-Tuning](https://github.com/oxylabs/LLM-Fine-Tuning) | Fine-tune an LLM on scraped Amazon data to generate product information |

Browse all repositories: [github.com/orgs/oxylabs/repositories](https://github.com/orgs/oxylabs/repositories)

Need something tailored to your project? Contact your Dedicated Account Manager, or reach the 24/7 support team through live chat or [support@oxylabs.io](mailto:support@oxylabs.io).

## Trust and responsible use

- **KYC and monitoring.** Oxylabs supports ethical and compliant use through Know Your Customer (KYC) checks, ongoing risk monitoring, and an Acceptable Use Policy.
- **Certified and audited.** The information security management system is certified to the ISO/IEC 27001:2022 standard for the scope set out in the Trust Center. Web API and Web Unblocker have completed independent SOC 2 Type 2 audits.
- **Your responsibility.** Customers remain responsible for ensuring their use of Oxylabs services complies with applicable laws, regulations, and third-party terms.

Learn more: [How does Oxylabs ensure compliance and ethical use of its services?](https://developers.oxylabs.io/help-center/most-popular-questions/how-does-oxylabs-ensure-compliance-and-ethical-use-of-its-services) or [Is web scraping legal?](https://developers.oxylabs.io/help-center/most-popular-questions/is-web-scraping-legal)

## Community and support

- **24/7 support:** live chat in the dashboard or email [support@oxylabs.io](mailto:support@oxylabs.io).
- **Documentation:** [developers.oxylabs.io](https://developers.oxylabs.io)
- **Community:** [YouTube](https://www.youtube.com/@oxylabs) · [X](https://x.com/oxylabs_io) · [LinkedIn](https://www.linkedin.com/company/oxylabs-io/)
- **What's new:** check our [Changelog](https://developers.oxylabs.io/changelog)
