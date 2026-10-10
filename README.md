<div align="center">

# Bishal Regmi

**Software engineer and data scientist**

Full-stack systems, machine learning pipelines, and the infrastructure that runs them.

[bishalregmi.com](https://bishalregmi.com) &nbsp;&middot;&nbsp; [LinkedIn](https://linkedin.com/in/bishalregmi)

</div>

---

I build software end to end: the data model, the API, the front end, and the
machine it runs on. Most of my side projects are self-hosted on a home NAS behind
Cloudflare, which keeps me honest about deployment, monitoring, and cost. On the
data side I care about results that hold up: point-in-time features, honest
baselines, and validation that matches how a model will actually be used.

## Featured work

| Project | What it does | Built with |
|---|---|---|
| **[World Cup 2026 Prediction Engine](https://bishalregmi.com/world-cup)** | Calibrated XGBoost model feeding a 2-million-run Monte Carlo simulator that forecast the 2026 FIFA World Cup. It reran daily through the tournament with every played match locked in, and each snapshot is versioned so you can watch the forecast move. | Python, XGBoost, FastAPI, PostgreSQL, Angular |
| **[ShowUpMD](https://showupmd.org)** | Civic app for Maryland voters. Enter an address to see your districts, representatives, candidates, and bills, and ask questions to a chat assistant grounded in real legislation through retrieval over pgvector. | Next.js, FastAPI, PostgreSQL, pgvector |
| **Research Portfolio** <br> [UI](https://github.com/regmibishal1/ResearchPortfolio-UI) &middot; [API](https://github.com/regmibishal1/ResearchPortfolio-FastAPI) | The platform behind bishalregmi.com: an Angular front end, a Spring Boot auth service, and a FastAPI model server, all in Docker on home hardware behind a Cloudflare Tunnel. | Angular, Spring Boot, FastAPI, Docker |
| **[Alzheimer's MRI Classification](https://bishalregmi.com/project/mri-classification)** | Benchmarked five ResNet depths for early Alzheimer's detection from brain MRI, with saliency maps to check which regions each model relies on. Deeper was not better. | Python, PyTorch |
| **[multisource_downloader](https://github.com/regmibishal1/multisource_downloader)** | Media archiver that pulls images and video from several social platforms. I built it to preserve footage from Nepal's 2025 anti-corruption protests. | Python |

## Lately

- Ran the World Cup engine through the full 2026 tournament; the site now grades
  the forecasts against what actually happened.
- Revisiting my early data science work on [the blog](https://bishalregmi.com/blog),
  most recently [rebuilding my first snowfall model](https://bishalregmi.com/blog/will-it-snow-tomorrow)
  with proper validation.
- Building a tool that repairs Google Photos Takeout exports: it restores EXIF
  metadata from the JSON sidecars and de-duplicates by perceptual hash, without
  ever touching the originals.

## How I work

- **Correctness before metrics.** No look-ahead, walk-forward validation, and
  baselines a model has to beat before it counts.
- **Honest results.** I would rather report a true null result than ship a leaky
  model that only looks good.
- **Own the whole path.** Typed APIs, reproducible pipelines, small reviewable
  commits, and a deployment I can rebuild from scratch.

## Toolbox

| Area | Tools |
|---|---|
| Languages | Python, Java, TypeScript, C#, SQL |
| Backend | FastAPI, Spring Boot, .NET |
| Front end | Angular, React, Next.js |
| Data and ML | pandas, scikit-learn, XGBoost, PyTorch, pgvector |
| Infrastructure | PostgreSQL, Docker, Cloudflare, AWS, Linux |
