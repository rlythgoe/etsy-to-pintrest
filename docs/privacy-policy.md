# Privacy Policy

**Effective date:** October 15, 2026

## Overview

This privacy policy describes how I use information in my personal
Etsy-to-Pinterest workflow for **SarahLythgoeArt**. This is a private
tool for my own use, not a service offered to other sellers or the
public.

The tool helps me retrieve information about my own Etsy listings and
use the OpenAI API to draft Pinterest titles, descriptions, and
keywords. Pinterest connection and publishing are not currently enabled.
If I add Pinterest account access or publishing, I will update this
policy to describe the information accessed and how it is used before
enabling those features.

## Information the tool processes

Depending on the features I use, the tool may process:

-   Etsy listing information, such as listing titles, descriptions,
    tags, listing URLs, listing IDs, and listing images.
-   Pinterest draft content generated from Etsy listing information,
    including titles, descriptions, and keywords.
-   Basic local usage records used to track AI-generation counts and
    estimated API costs.
-   Authentication credentials needed to connect to Etsy. The Etsy
    access token is currently held in server memory and is cleared when
    the server process stops. API keys are kept in the development
    environment's secrets rather than in public source code.

The tool is intended to process information from my own Etsy shop. I do
not intend to collect information from other Etsy sellers or from
members of the public.

## How information is used

I use this information only to operate and improve my personal workflow,
including to:

-   Retrieve and identify my own active Etsy listings.
-   Generate draft Pinterest copy for a listing I choose, or for the
    next eligible listing when I use automatic selection.
-   Save and review drafts before deciding whether to use them.
-   Track estimated AI usage and enforce local generation limits.

The tool does not automatically publish Pins. Any future Pinterest
publishing feature will require a deliberate action by me for each Pin.

## Third-party services

**Etsy.** The tool connects to Etsy using Etsy's API and the permissions
I authorize. Etsy's own terms and privacy practices apply to Etsy's
services.

**OpenAI API.** When I request Pinterest copy, the listing title, a
limited portion of the listing description, and selected Etsy tags are
sent to the OpenAI API to generate text. The generated response is
returned to the tool for review and storage. OpenAI's applicable API
terms and privacy documentation govern OpenAI's processing of API inputs
and outputs.

**GitHub Codespaces and GitHub.** The application code and local
draft/usage files are maintained in my development workspace. Access to
that workspace is controlled by the relevant GitHub account and
repository settings. GitHub's own terms and privacy practices apply to
its services.

**Pinterest.** Pinterest account data is not currently accessed by this
tool, and Pins are not currently published by it. If Pinterest
integration is enabled later, the tool may access the Pinterest account
and boards I authorize and may publish only the Pins I explicitly choose
to publish. This policy will be updated to reflect the actual
implementation.

## Sharing and sale

I do not sell personal information or use this tool to serve
advertisements. I do not intentionally share Etsy listing information or
generated drafts with other sellers or the public. Information is sent
to the third-party providers described above only as needed to operate
the features I use.

## Storage and security

Drafts and usage records are stored in local files in the development
workspace. The application is a personal project and is not a public
service. I take reasonable steps to keep API keys and authentication
credentials out of source code and public repositories. No method of
storage or transmission can be guaranteed completely secure.

The current Etsy access token is held in server memory and is lost when
the server restarts. The application may need to reconnect to Etsy after
a restart. This policy will be updated if the app's credential storage
or connected services change.

## Retention and deletion

I keep draft and usage information for as long as I need it for this
personal workflow. I can remove saved drafts from the local queue and
delete local usage or feedback files. Deleting local files does not
delete records held by Etsy, OpenAI, GitHub, or other third-party
providers under their own policies.

I can also revoke the tool's authorization through the relevant
third-party account settings. Revoking authorization may prevent the
corresponding integration from working.

## Changes to this policy

I may update this policy when the tool's features or data practices
change. The effective date at the top will be revised when I make a
material update.

## Contact

For questions about this personal tool or this policy, contact me
through the **SarahLythgoeArt** Etsy shop:
https://www.etsy.com/shop/SarahLythgoeArt
