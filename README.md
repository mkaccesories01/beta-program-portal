# beta-program-portal

A small web app for running the mobile beta. People can apply, accepted testers get TestFlight invites, and everyone can send feedback in one place instead of scattered emails and DMs. On October 10 we capped the program at **200 external testers** to keep the feedback manageable, and the portal enforces that limit.

Recruitment begins right after this ships. We still haven't decided between promoting the beta to our email list or on social channels, so the sign-up form records where each applicant came from. That way the data can settle it after the first week.

## How it works

Applicants answer a short form about their device and how they use the product today. Approved testers are synced to TestFlight, and their in-app feedback is tagged with build numbers from [`mobile-ci-pipeline`](https://github.com/mkaccesories01/mobile-ci-pipeline). That makes it easy to see which issues are fixed in which build.

## Timeline

The beta opens November 15 and runs until the public launch on December 15. When the beta ends, the portal will be repurposed to coordinate the Product Hunt launch described in the go-to-market strategy.
