# Event-Integrator Documentation

Official documentation and guides for Event-Integrator platform.

## Contents

### Getting Started
- [Installation Guide](docs/getting-started/installation.md)
- [Quick Start Tutorial](docs/getting-started/quick-start.md)
- [Configuration Basics](docs/getting-started/configuration.md)

### Core Concepts
- [Architecture Overview](docs/concepts/architecture.md)
- [Event Model](docs/concepts/events.md)
- [Processing Pipeline](docs/concepts/pipeline.md)
- [Handlers and Transformers](docs/concepts/handlers.md)

### API Reference
- [REST API](docs/api/rest.md)
- [SDK Documentation](docs/api/sdk.md)
- [Webhook Payloads](docs/api/webhooks.md)
- [Configuration Schema](docs/api/config-schema.md)

### Integration Guides
- [GitHub Actions Integration](docs/integrations/github-actions.md)
- [GitLab CI Integration](docs/integrations/gitlab-ci.md)
- [Jenkins Integration](docs/integrations/jenkins.md)
- [AWS Lambda Integration](docs/integrations/aws-lambda.md)
- [Kubernetes Deployment](docs/integrations/kubernetes.md)

### Troubleshooting
- [Common Issues](docs/troubleshooting/common-issues.md)
- [Performance Tuning](docs/troubleshooting/performance.md)
- [Debugging Guide](docs/troubleshooting/debugging.md)
- [FAQ](docs/troubleshooting/faq.md)

### Migration Guides
- [Upgrading from v1 to v2](docs/migration/v1-to-v2.md)
- [Breaking Changes](docs/migration/breaking-changes.md)

## Building the Documentation

```bash
# Install dependencies
npm install

# Build documentation
npm run build

# Start local server
npm run serve
```

Documentation will be available at `http://localhost:3000`

## Contributing to Docs

We welcome documentation contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

Creative Commons Attribution 4.0 International - see LICENSE file for details
