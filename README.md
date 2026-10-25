# ever-bright-receptionist
## Setup notes

Business config and environment template for an AI phone receptionist for Ever Bright Laundry, built on [kirklandsig/AIReceptionist](https://github.com/kirklandsig/AIReceptionist) (AGPL-3.0).

- `config/businesses/ever-bright-laundry.yaml`: copy into `config/businesses/` of the AIReceptionist code. Replace the placeholder transfer number and email, and the `TODO` hours, prices and turnaround times.
- `.env.example`: copy to `.env` in that project and fill in your LiveKit, OpenAI and Gmail app-password values.
