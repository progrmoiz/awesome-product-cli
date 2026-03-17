# Awesome Product CLIs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of command-line interfaces for SaaS products and services, making every product accessible to AI agents and developers from the terminal.

The era of AI agents is here. Agents work best through structured, composable command-line interfaces — not GUIs. This list tracks every SaaS product that ships a CLI, so developers and AI agents can discover and use them.

## Contents

- [Cloud and Infrastructure](#cloud-and-infrastructure)
- [Databases](#databases)
- [Payments and Finance](#payments-and-finance)
- [Communication and Email](#communication-and-email)
- [Developer Tools](#developer-tools)
- [Auth and Identity](#auth-and-identity)
- [CMS and Content](#cms-and-content)
- [Monitoring and Observability](#monitoring-and-observability)
- [AI and ML](#ai-and-ml)
- [CI/CD](#cicd)
- [Search](#search)
- [Infrastructure as Code](#infrastructure-as-code)
- [Other](#other)
- [Products Without CLIs](#products-without-clis)

## Cloud and Infrastructure

- [Vercel CLI](https://github.com/vercel/vercel) - Deploy, preview, and ship from the terminal with full project management.
- [Netlify CLI](https://github.com/netlify/cli) - Deploy sites, manage environment variables, run local dev server, and manage serverless functions.
- [Railway CLI](https://github.com/railwayapp/cli) - Create projects, link repos, pull environment variables, and create services and databases.
- [Fly.io CLI](https://github.com/superfly/flyctl) - Deploy and manage applications on Fly.io edge infrastructure.
- [Render CLI](https://github.com/render-oss/cli) - Manage Render services, databases, and deployments.
- [Cloudflare Wrangler](https://github.com/cloudflare/workers-sdk) - Build, deploy, and manage Cloudflare Workers, KV, R2, D1, and more.
- [Heroku CLI](https://github.com/heroku/cli) - Full platform management for apps, databases, pipelines, add-ons, logs, and scaling.
- [DigitalOcean CLI](https://github.com/digitalocean/doctl) - Manage droplets, Kubernetes, databases, apps, domains, and billing.
- [AWS CLI](https://github.com/aws/aws-cli) - Universal CLI for all AWS services with comprehensive JSON output support.
- [Google Cloud CLI](https://cloud.google.com/sdk/docs/install) - Manage GCP resources including compute, storage, databases, ML, and networking.
- [Azure CLI](https://github.com/Azure/azure-cli) - Manage Azure resources including VMs, storage, databases, and AI services.
- [Firebase CLI](https://github.com/firebase/firebase-tools) - Deploy Firebase hosting, functions, Firestore rules, and auth configuration.
- [Deno Deploy CLI](https://github.com/denoland/deno) - Deploy to Deno Deploy and manage projects, built into the Deno runtime.
- [Upstash CLI](https://github.com/upstash/cli) - Manage Redis and Kafka databases on Upstash from the terminal.

## Databases

- [Supabase CLI](https://github.com/supabase/cli) - Run Supabase locally, manage migrations, deploy edge functions, and generate types.
- [PlanetScale CLI](https://github.com/planetscale/cli) - Manage branches, deploy requests, and schema changes with a git-like workflow.
- [Turso CLI](https://github.com/tursodatabase/turso-cli) - Manage databases, groups, and replicas on Turso libSQL edge database.
- [Neon CLI](https://github.com/neondatabase/neonctl) - Manage Neon Serverless PostgreSQL projects, branches, databases, and roles.
- [MongoDB Atlas CLI](https://github.com/mongodb/mongocli) - Manage Atlas clusters, backups, users, and alerts.
- [Xata CLI](https://github.com/xataio/client-ts) - Manage Xata serverless database branches, schemas, migrations, and codegen.
- [Convex CLI](https://github.com/get-convex/convex-js) - Manage Convex backend, deploy functions, manage data, and run dev server.

## Payments and Finance

- [Stripe CLI](https://github.com/stripe/stripe-cli) - Test webhooks, tail API logs, trigger events, and CRUD any Stripe API object.

## Communication and Email

- [Resend CLI](https://github.com/resend/resend-cli) - Send emails, manage domains, and run diagnostics with auto-JSON when piped to agents.
- [Twilio CLI](https://github.com/twilio/twilio-cli) - Send SMS, make calls, manage phone numbers, and view logs.
- [Postmark CLI](https://github.com/ActiveCampaign/postmark-cli) - Manage and preview email templates locally with push and pull commands.
- [Slack CLI](https://github.com/slackapi/slack-cli) - Create, develop, and deploy Slack apps from the command line.

## Developer Tools

- [GitHub CLI](https://github.com/cli/cli) - Pull requests, issues, repos, releases, actions, and codespaces with field-level JSON selection.
- [GitLab CLI](https://github.com/gitlab-org/cli) - Merge requests, issues, CI/CD pipelines, and repository management.
- [Sentry CLI](https://github.com/getsentry/sentry-cli) - Upload sourcemaps and debug symbols, manage releases, and view issues.
- [Doppler CLI](https://github.com/DopplerHQ/cli) - Manage secrets, inject environment variables into processes, and manage projects.
- [HashiCorp Vault CLI](https://github.com/hashicorp/vault) - Manage secrets, encryption, and identity with read and write operations.
- [Shopify CLI](https://github.com/Shopify/cli) - Build Shopify apps, themes, and Hydrogen storefronts.
- [1Password CLI](https://developer.1password.com/docs/cli/) - Manage vaults, items, and secrets with an SSH agent.

## Auth and Identity

- [Auth0 CLI](https://github.com/auth0/auth0-cli) - Manage applications, APIs, users, roles, connections, and actions.
- [Clerk CLI](https://github.com/clerk/cli) - Manage Clerk auth resources from the terminal.
- [WorkOS CLI](https://github.com/workos/cli) - Integrate WorkOS AuthKit into your application.

## CMS and Content

- [Sanity CLI](https://github.com/sanity-io/sanity) - Init projects, manage datasets, deploy studios, and run GraphQL API.
- [Contentful CLI](https://github.com/contentful/contentful-cli) - Manage spaces, export and import content, run migrations, and manage extensions.
- [Strapi CLI](https://github.com/strapi/strapi) - Generate projects, content types, APIs, and plugins.
- [Payload CLI](https://github.com/payloadcms/payload) - Project scaffolding and generation for Payload CMS.

## Monitoring and Observability

- [Datadog CLI](https://github.com/DataDog/datadog-ci) - Upload sourcemaps, manage synthetics, trace CI pipelines, and upload test results.
- [Grafana CLI](https://github.com/grafana/grafana) - Manage dashboards, data sources, plugins, and alerts.
- [Axiom CLI](https://github.com/axiomhq/cli) - Manage datasets, run queries, and stream logs on Axiom observability platform.

## AI and ML

- [OpenAI CLI](https://github.com/openai/openai-python) - Make API calls, manage fine-tuning jobs, and upload files from the terminal.
- [Replicate CLI](https://github.com/replicate/cli) - Run models, create predictions, stream output, and manage trainings.
- [Hugging Face CLI](https://github.com/huggingface/huggingface_hub) - Download and upload models and datasets, manage repos, and run inference.

## CI/CD

- [CircleCI CLI](https://github.com/CircleCI-Public/circleci-cli) - Validate configs, run jobs locally, manage orbs, and manage contexts.
- [Buildkite CLI](https://github.com/buildkite/cli) - Manage builds, pipelines, and agents from the terminal.

## Search

- [Algolia CLI](https://github.com/algolia/cli) - Manage indices, records, API keys, synonyms, and rules.
- [Meilisearch](https://github.com/meilisearch/meilisearch) - Self-hosted search engine with CLI for starting and configuring the server.
- [Typesense](https://github.com/typesense/typesense) - Self-hosted search engine with server binary management via config flags.

## Infrastructure as Code

- [Terraform CLI](https://github.com/hashicorp/terraform) - Manage cloud resources across providers with infrastructure as code.
- [Pulumi CLI](https://github.com/pulumi/pulumi) - Infrastructure as code with real programming languages across cloud providers.

## Other

- [Expo CLI](https://github.com/expo/expo) - Build, deploy, and update React Native apps with EAS builds and submissions.
- [Prisma CLI](https://github.com/prisma/prisma) - Database toolkit for migrations, schema management, studio, and type generation.
- [Cloudinary CLI](https://github.com/cloudinary/cloudinary-cli) - Upload, manage, and transform media assets on Cloudinary.
- [Google Workspace CLI](https://github.com/googleworkspace/cli) - Interact with Google Workspace APIs including Drive, Calendar, Gmail, and Sheets.

## Products Without CLIs

Notable SaaS products that do not have a CLI yet — opportunities for community-built CLIs.

- [Paddle](https://developer.paddle.com/) - Payments platform, API-only.
- [Lemon Squeezy](https://docs.lemonsqueezy.com/) - Payments platform, API-only.
- [Notion](https://developers.notion.com/) - Productivity and docs, API and MCP only.
- [Airtable](https://airtable.com/developers) - Spreadsheet database, API-only.
- [Linear](https://developers.linear.app/) - Project management, API and MCP only.
- [PostHog](https://posthog.com/docs/api) - Product analytics, API-only.
- [Mailgun](https://documentation.mailgun.com/) - Email service, no dedicated CLI.
- [Anthropic](https://docs.anthropic.com/) - AI platform, SDK only, no CLI binary.

## Contributing

Contributions welcome! Please read the [contributing guidelines](contributing.md) first.

## Footnotes

Know a SaaS product CLI that is missing? [Open an issue](https://github.com/progrmoiz/awesome-product-cli/issues) or submit a pull request.
