# ECHO SITES — Static Web Deployments

> All public-facing Echo Universe websites, recovered and version-controlled.
> Each subdirectory is a standalone site ready for Cloudflare Pages deployment.

---

## Sites

| Directory | Site Name | Status | Target URL |
|-----------|-----------|--------|------------|
| `echonate-nexus/` | EchoNate Nexus | ✅ Recovered | `echonexus.com` |
| `tax-services/` | Tax Services Landing | ✅ Recovered | `tax.echonexus.com` |
| `mielesy/` | The Mielesy Experience | ✅ Recovered | `mielesy.echonexus.com` |
| `organism-dashboard/` | Echo Universe Organism Dashboard | ✅ Recovered | `organism.echonexus.com` |
| `sherlock-hub/` | Sherlock Hub | ✅ Recovered | `sherlock.echonexus.com` |

---

## Deploy to Cloudflare Pages

Each site deploys independently. Connect this repo to Cloudflare Pages and set the build output directory to the site's subdirectory.

```bash
# Example: deploy echonate-nexus
Build command: (none — static HTML)
Build output directory: echonate-nexus
```

---

## Part of the Echo Universe

See [manus-fleet](https://github.com/onlyecho822-source/manus-fleet) for the full fleet registry and health monitoring.
