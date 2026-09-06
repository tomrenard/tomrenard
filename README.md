# Tom Renard

**Senior Product Engineer, Berlin.** I build the customer facing parts of products and own what happens after they ship.

Currently at **Aroundhome**, a marketplace for home improvement: homeowners describe a project, we match them with vetted local trade companies, and the partner pays for the introduction, not the homeowner. I take features from the first conversation to the number they move, which means shaping the requirement with product and design, building it wherever it needs to be built, then owning the rollout and the read on whether it worked.

Frontend is where I am deepest, and the decisions I care about are the ones with system wide consequences: what runs in the browser at all, where the client and server line sits, and how a design system gets adopted rather than just designed. Under React there is a web platform, and that is where scaled frontends break. I go into the Go and Ruby services when the problem lives there, and into the infrastructure when it lives there instead.

The longer version of that, with the work each position came from, is at [tomrenard.site/craft](https://tomrenard.site/craft).

**Stack:** TypeScript, React, Next.js, Astro, Tailwind, Go, Ruby, GraphQL, Postgres, Terraform, Playwright, Vitest.

## What I build on my own time

The common thread is guardrails: making a system prove its own claims before I trust it.

- **[EuroLens](https://github.com/tomrenard/eurolens).** Tracks European Parliament votes and explains them in plain English. It used to use a language model for the explanations; I removed it, because a tool claiming to be non partisan cannot afford to invent a fact. Explanations now come from the official record through a fixed glossary.
- **Repères 2027** (private). Voting advice app for the French presidential election. Every candidate position needs a dated source and the build fails if one is missing. No server, so answers never leave the browser.
- **Wattson and Sparfuchs** (private, they hold my own health and money data). A personal endurance coach and a personal tax advisor. Scripts do the calculations, the model only gives an opinion on the result.
- **llm-vps** (not published yet). A self hosted OpenAI compatible endpoint as code. The README opens with a cost table and then concedes when not to use it.

[tomrenard.site](https://tomrenard.site) · [LinkedIn](https://www.linkedin.com/in/tom-renard-2021/)
