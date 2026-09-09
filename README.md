# CFnew automatic release deployment

Fork of byJoey/cfnewup. The release-sync workflow checks byJoey/cfnew every six hours.

Cloudflare Pages builds the main branch. Environment credentials and the C namespace binding are managed only in Cloudflare, never in this repository.

Upstream releases replace _worker.js. Local changes to that file may be overwritten. Scheduled jobs and platform deployments can fail or be delayed; inspect the Actions and Pages histories if updates stop.
