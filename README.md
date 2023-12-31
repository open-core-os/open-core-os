# open-core-os

There are plenty of awesome lists of open-source tools (like [Runa's](https://github.com/RunaCapital/awesome-oss-alternatives) or [this one](https://github.com/sereneblue/awesome-oss)). They're all huge, which is expected if the purpose of the list is to cover all available tools. Which means that for solving each specific problem at hand there are multiple tools listed, and someone who hears about the tool for the first time needs to do their own research to decide which of the options to use.

But what if less is more? The purpose of this list is to provide a much shorter curation of leading open-source tools, specifically developer infrastructure tools. The idea is based on the following observation: for many common problems there is sort of a "duopoly": one leading product that isn't open source (typically SaaS), and their open source counterpart (typically "open core" with a permissive license for the Community Edition combined and an Enterprise tier with extra paid features). The canonical example is the GitHub and Gitlab: both products solve the problem of code collaboration, one in a SaaS way, another in a self-managed open-core way.

Why OS? Because taken together, these tools are effectively the operating system of a software team. This is what terms like DevOps and more recently Platform Engineering are about. The only difference with a traditional definition of an operating system is the hardware: it's not individual laptops or servers, but rather hundreds of services spread across dozens of data centers. One can think of the APIs provided by the likes of AWS as "new hardware"; the collection of tools under this "new OS" umbrella is what holds it all together. The OS framing also allows to exclude tools that are not part of developer infrastructure (like calendars, CRMs etc).

# Infrastructure

| Problem at hand  | Leading SaaS | Leading open-core |
| ------------- | ------------- | ------------- |
| Code collaboration  | [GitHub](https://github.com) | [GitLab](https://gitlab.com) |
| Observability  | [Datadog](https://datadog.com)  | [SigNoz](https://signoz.com) |
| SecretOps | [Doppler](https://doppler) | [Infisical](https://infisical.com) |
| ETL | [Fivetran](https://www.appsmith.com/) | [Airbyte](https://airbyte.com) |
| IaC management | [Terraform Cloud](https://terraform.io) | [Digger](https://digger.dev) |

# Application

| Problem at hand  | Leading SaaS | Leading open-core |
| ------------- | ------------- | ------------- |
| Backend-as-a-service | [Firebase](https://firebase.com) | [Supabase](https://supabase.com) |
| Feature flags | [LaunchDarkly](launchdarkly.com) | [Unleash](https://www.getunleash.io/) |
| Internal tool builder | [Retool](retool.com) | [AppSmith](https://www.appsmith.com/) |
| Workflow automation | [Zapier](zapier.com) | [N8N](https://n8n.io/) |
| API development | [Postman](https://postman.com) | [Hoppscotch](https://github.com/hoppscotch/hoppscotch) |
| Event collection | [Segment](https://segment.com) | [Jitsu](https://jitsu.com/) |


