# Phono Technologies

Cloud infrastructure consulting and open-source developer tools.

We provide specialized cloud infrastructure services to technology companies and maintain open-source tooling for DevOps and platform engineering teams.

---

## Open Source Projects

### [CICosts](https://github.com/phonotechnologies/cicosts-app)

GitHub Actions cost tracking. See per-workflow, per-repository, and per-branch spend in real time. Installs as a GitHub App with no code changes required.

[![GitHub Stars](https://img.shields.io/github/stars/phonotechnologies/cicosts-app?style=flat-square)](https://github.com/phonotechnologies/cicosts-app)
[![MIT License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://github.com/phonotechnologies/cicosts-app/blob/main/LICENSE)

Free and MIT licensed. Hosted at [app.cicosts.dev](https://app.cicosts.dev).

---

### [envaudit](https://github.com/phonotechnologies/envaudit)

Rust CLI to detect `.env` drift across environments, validate files against `.env.example`, and scan for accidentally committed secrets.

```bash
cargo install envaudit

envaudit scan       # compare .env files across environments
envaudit check      # validate .env against .env.example (CI-friendly, exits 1 on failure)
envaudit secrets    # detect high-entropy values and known secret patterns
```

[![GitHub Stars](https://img.shields.io/github/stars/phonotechnologies/envaudit?style=flat-square)](https://github.com/phonotechnologies/envaudit)
[![MIT License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://github.com/phonotechnologies/envaudit/blob/main/LICENSE)

---

## Services

Cloud infrastructure consulting: AWS, Kubernetes, Terraform, CI/CD pipelines.

[phonotech.ca](https://phonotech.ca) | [hello@phonotech.ca](mailto:hello@phonotech.ca)
