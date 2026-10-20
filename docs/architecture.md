# Website architecture

| Component | Project role |
| --- | --- |
| Google Sites | Visual page authoring and website hosting |
| Cloudflare | Domain/DNS management |
| GitHub | Public project documentation and change history |

The project connected a custom business domain to Google Sites. Exact DNS targets and verification records are not reproduced here. Cloudflare DNS management should not be confused with GitHub hosting the site or with the site's application backend.

## Maintenance workflow

Edit and preview website content in Google Sites, publish the intended changes, then verify public navigation and mobile layout. Make domain changes in the domain/DNS management interface and verify the published address separately. Record meaningful architecture and content changes in this repository.

This document describes the division of responsibilities; it does not claim that current DNS records or the current live site were inspected during the GitHub import.
