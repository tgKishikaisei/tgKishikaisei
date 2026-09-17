<p align="center">
  <a href="https://kietos.me">
    <img src="https://kietos.me/img/github.png" width="100%"
         alt="Behruz Avezmatov — full-stack developer, Tashkent, kietos.me">
  </a>
</p>

<p align="center">
  <a href="https://kietos.me"><img alt="Portfolio" src="https://img.shields.io/badge/portfolio-kietos.me-00A692?style=flat-square"></a>
  <a href="https://kietos.me/pricing"><img alt="Prices" src="https://img.shields.io/badge/prices%20and%20estimate-%2Fpricing-00A692?style=flat-square"></a>
  <a href="https://t.me/kietos_bot?start=request"><img alt="Request via bot" src="https://img.shields.io/badge/leave%20a%20request-bot-00A692?style=flat-square&logo=telegram&logoColor=white"></a>
  <a href="https://t.me/BehruzAvezmatov"><img alt="Telegram" src="https://img.shields.io/badge/write%20to%20me-Telegram-00A692?style=flat-square&logo=telegram&logoColor=white"></a>
</p>

I build Telegram bots, FastAPI backends and fast websites, and ship them to
production with Docker, tests and CI. Open to freelance projects — I reply
within a day.

## What I do

**Pipelines where data must not leave the server.** In SafeFlow I mask personal
data before a language model ever sees it: Presidio finds it, RabbitMQ carries
the work, a local model answers through Ollama, Redis keeps the state. Nothing
leaves the perimeter, and every step can be verified on its own.

**Video and image analysis.** Bubble Tracker detects bubbles on video with a
six-stage frame preprocessing; the PPE monitor flags whether protective gear is
worn. OpenCV and NumPy, tuned until it holds on real footage and not only on a
demo clip.

**Services with roles and a trail you can audit.** The backend of this site:
login with TOTP two-factor, refresh tokens that die when reused, an append-only
audit log the application itself cannot rewrite, rate limits, an admin page that
answers a plain 404 to everyone without the key, and a decoy that reports
scanners instead of feeding them.

**APIs and backends.** FastAPI and PostgreSQL: schema and migrations first,
permission checks on every endpoint, queues for the long jobs, OpenAPI as the
contract, tests on what breaks quietly.

**Telegram bots.** Catalogs, carts, payments, bookings, alerts to the owner. The
bot of this site takes requests, quotes prices and collects reviews — and it
reads the same data as the website, so the two cannot start telling different
things.

**Websites.** Landing pages and sites with their own backend and admin panel:
two languages, motion, WebGL scenes, and accessibility at 95+ in Lighthouse on
every build, checked in CI rather than promised.

**Deployment and keeping it alive.** Docker Compose, nginx, TLS, fail2ban,
backups and CI on every commit — one command to deploy, one to roll back.

## Stack

**Backend**

![Python](https://img.shields.io/badge/Python-00A692?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-00A692?style=flat-square&logo=fastapi&logoColor=white)
![Starlette](https://img.shields.io/badge/Starlette-00A692?style=flat-square)
![Uvicorn](https://img.shields.io/badge/Uvicorn-00A692?style=flat-square)
![Pydantic](https://img.shields.io/badge/Pydantic%20v2-00A692?style=flat-square&logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy%202.0-00A692?style=flat-square&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-00A692?style=flat-square)
![aiogram](https://img.shields.io/badge/aiogram-00A692?style=flat-square&logo=telegram&logoColor=white)
![Django](https://img.shields.io/badge/Django-00A692?style=flat-square&logo=django&logoColor=white)
![Jinja](https://img.shields.io/badge/Jinja-00A692?style=flat-square&logo=jinja&logoColor=white)
![httpx](https://img.shields.io/badge/httpx-00A692?style=flat-square)
![slowapi](https://img.shields.io/badge/slowapi-00A692?style=flat-square)
![PyJWT](https://img.shields.io/badge/PyJWT-00A692?style=flat-square&logo=jsonwebtokens&logoColor=white)
![aiosmtplib](https://img.shields.io/badge/aiosmtplib-00A692?style=flat-square)
![OpenAPI](https://img.shields.io/badge/OpenAPI-00A692?style=flat-square&logo=openapiinitiative&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-00A692?style=flat-square)
![uv](https://img.shields.io/badge/uv-00A692?style=flat-square&logo=astral&logoColor=white)

**Data, queues, models**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0E5F52?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-0E5F52?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-0E5F52?style=flat-square&logo=rabbitmq&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-0E5F52?style=flat-square&logo=sqlite&logoColor=white)
![psycopg](https://img.shields.io/badge/psycopg%203-0E5F52?style=flat-square)
![Presidio](https://img.shields.io/badge/Presidio-0E5F52?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-0E5F52?style=flat-square&logo=ollama&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-0E5F52?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-0E5F52?style=flat-square&logo=numpy&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-0E5F52?style=flat-square)

**Frontend**

![JavaScript](https://img.shields.io/badge/JavaScript-00473C?style=flat-square&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-00473C?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-00473C?style=flat-square&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-00473C?style=flat-square&logo=vite&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP%20ScrollTrigger-00473C?style=flat-square&logo=greensock&logoColor=white)
![Lenis](https://img.shields.io/badge/Lenis-00473C?style=flat-square)
![three.js](https://img.shields.io/badge/three.js-00473C?style=flat-square&logo=threedotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-00473C?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-00473C?style=flat-square&logo=css&logoColor=white)
![PWA](https://img.shields.io/badge/PWA%20%2B%20Service%20Worker-00473C?style=flat-square)
![Web Components](https://img.shields.io/badge/Intl%20%2B%20a11y-00473C?style=flat-square)

**Tests and quality**

![pytest](https://img.shields.io/badge/pytest-0E5F52?style=flat-square&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-0E5F52?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-0E5F52?style=flat-square)
![happy-dom](https://img.shields.io/badge/happy--dom-0E5F52?style=flat-square)
![Ruff](https://img.shields.io/badge/Ruff-0E5F52?style=flat-square&logo=ruff&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-0E5F52?style=flat-square&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-0E5F52?style=flat-square&logo=prettier&logoColor=white)
![bandit](https://img.shields.io/badge/bandit-0E5F52?style=flat-square)
![pip-audit](https://img.shields.io/badge/pip--audit-0E5F52?style=flat-square)
![Lighthouse CI](https://img.shields.io/badge/Lighthouse%20CI-0E5F52?style=flat-square&logo=lighthouse&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-041716?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-041716?style=flat-square&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-041716?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-041716?style=flat-square&logo=linux&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-041716?style=flat-square&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-041716?style=flat-square&logo=gnubash&logoColor=white)
![systemd](https://img.shields.io/badge/systemd%20%2B%20journald-041716?style=flat-square)
![Git](https://img.shields.io/badge/Git-041716?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-041716?style=flat-square&logo=githubactions&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's%20Encrypt%20%2B%20certbot-041716?style=flat-square&logo=letsencrypt&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-041716?style=flat-square&logo=cloudflare&logoColor=white)
![Umami](https://img.shields.io/badge/Umami-041716?style=flat-square&logo=umami&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-041716?style=flat-square&logo=trivy&logoColor=white)
![resvg](https://img.shields.io/badge/resvg-041716?style=flat-square)

**Security I actually implement**

![JWT](https://img.shields.io/badge/JWT%20with%20rotation-00473C?style=flat-square&logo=jsonwebtokens&logoColor=white)
![TOTP](https://img.shields.io/badge/TOTP%202FA-00473C?style=flat-square)
![Argon2](https://img.shields.io/badge/Argon2id-00473C?style=flat-square)
![CSP](https://img.shields.io/badge/CSP%20%2B%20Trusted%20Types-00473C?style=flat-square)
![Rate limiting](https://img.shields.io/badge/rate%20limiting-00473C?style=flat-square)
![fail2ban](https://img.shields.io/badge/fail2ban%20%2B%20ufw-00473C?style=flat-square)
![Turnstile](https://img.shields.io/badge/Turnstile-00473C?style=flat-square&logo=cloudflare&logoColor=white)
![Audit log](https://img.shields.io/badge/append--only%20audit%20log-00473C?style=flat-square)
![Least privilege](https://img.shields.io/badge/least--privilege%20DB%20roles-00473C?style=flat-square)

## How the system works

kietos.me on one server: nginx in front, four containers behind it, one database.

```mermaid
flowchart LR
  visitor["Visitor"] -->|HTTPS| nginx
  tg["Telegram"] <--> bot

  subgraph server["One server · Docker Compose"]
    nginx["nginx<br/>TLS · security headers<br/>rate limits · clean URLs"]
    site["Static site<br/>Vite build · PWA<br/>12 pages · ru + en"]
    api["API<br/>FastAPI · Pydantic<br/>SQLAlchemy 2.0"]
    bot["Bot<br/>aiogram · long polling"]
    umami["Umami<br/>self-hosted analytics"]
    db[("PostgreSQL<br/>Alembic migrations<br/>append-only audit log")]
  end

  nginx --> site
  nginx -->|api.kietos.me| api
  nginx -->|/u/script.js| umami
  api --> db
  bot --> db
  umami --> db
  api -->|new request, alarms| tg
  api -->|SMTP| mail["Mail"]
  api -->|verify| turnstile["Cloudflare Turnstile"]
  bot -->|weekly report| tg

  classDef inside fill:#041716,stroke:#00A692,color:#a3dbcf
  classDef outside fill:#00473C,stroke:#00A692,color:#a3dbcf
  class nginx,site,api,bot,db,umami inside
  class visitor,tg,mail,turnstile outside
```

And how a change reaches production:

```mermaid
flowchart LR
  commit["git commit"] --> ci["CI<br/>Ruff · ESLint · Prettier<br/>Vitest · pytest · Playwright<br/>Lighthouse · bandit · pip-audit"]
  ci --> build["npm run build<br/>CSP hashes · prerender · sitemap"]
  build --> deploy["deploy.sh<br/>upload to a temp folder<br/>swap in one move"]
  deploy --> live["kietos.me"]
  deploy -.->|previous version kept| rollback["one command to roll back"]

  classDef step fill:#041716,stroke:#00A692,color:#a3dbcf
  class commit,ci,build,deploy,live,rollback step
```

## Selected work

| Project                                                                                   | What it is                                                                | Stack                       |
| ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | --------------------------- |
| [kietos.me](https://kietos.me)                                                            | My portfolio: site, FastAPI backend, admin panel with 2FA and its own bot | FastAPI · PostgreSQL · Vite |
| [telegrambot_magazine](https://github.com/tgKishikaisei/telegrambot_magazine)             | Telegram shop bot: catalog, cart, checkout, order alerts for the admin    | aiogram · SQLAlchemy        |
| [Platejnaya_sistema_FastAPI](https://github.com/tgKishikaisei/Platejnaya_sistema_FastAPI) | Payment service: accounts, transfers, operation history                   | FastAPI · SQLAlchemy        |
| [site_shop_django](https://github.com/tgKishikaisei/site_shop_django)                     | Django shop: catalog, cart, admin panel                                   | Django · Bootstrap          |

---

<p align="center">
  фулстек-разработчик из Ташкента — Telegram-боты, API и сайты под ключ.<br>
  Цены, калькулятор стоимости и заявка — <a href="https://kietos.me">kietos.me</a>
</p>
