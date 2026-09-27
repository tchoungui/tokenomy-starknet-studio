# Tokenomy Starknet Studio

This public repository contains a static evidence and readiness showcase for the Starknet studio. It contains only an HTML landing page, a GitHub App manifest draft and this README. It is not a deployed dApp or a smart-contract implementation.

Both the Celo/EVM and Starknet studios are operated by Tokenomy under common ownership. Their technical work and grant budgets are separate. They are not represented as unrelated organizations.

## Files

- `index.html`: the reviewed public readiness page.
- `github-app-manifest.json`: a minimal private GitHub App registration draft; metadata-read permission only, no events or OAuth-on-install.

## Actual status

The public showcase repository is hosted under `tchoungui`. Published under `tchoungui` on 2026-09-27. `tokenomy-world` returned HTTP 403 because this account is not a member. That is an access boundary, not a paid-plan limit. The manifest is prepared for that intended owner. App registration, app installation, Marketplace review and live testnet-demo verification remain pending.

No grant award, production dApp, security audit or grant application is claimed. Official grant references were reviewed on 27 September 2026 and must be checked again before relying on eligibility or deadlines. The Celo implementation-evidence gap on the page refers to application/contract source, not this static showcase repository.

AgentX showcase destination: https://my-agentx101.tokenomy.world/showcase/starknet/ . Use the deployment report to confirm when that destination is live. GitHub Pages, if enabled, serves this same static page; configuration alone does not prove a completed build.

## Registering the dedicated app

An authorized owner must review the manifest in GitHub's app registration UI, confirm the account, use a unique app name, keep it private, disable webhooks, and install only on this studio's selected repositories. Store any app private key in the encrypted credentials vault; never upload credentials, private application source or wallet recovery words here.

See https://docs.github.com/en/apps/sharing-github-apps/registering-a-github-app-from-a-manifest . A manifest file is not a registered or verified app.
