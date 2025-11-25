# NovaCloud EIP Documentation

Enterprise Integration Platform - Novatek EIP

## Quick Start

### Prerequisites
- Docker & Docker Compose
- 16GB+ RAM
- Node.js 18+

### Installation

```bash
# Clone and setup
git clone https://github.com/novatek-dev/docs.git
cd docs

# Install Mintlify CLI
npm i -g mint

# Start preview
mint dev
```

Visit `http://localhost:3000` to view documentation.

## Technology Stack

- **Frontend:** Next.js + React
- **Database:** Supabase (PostgreSQL) + Neo4j Graph DB
- **AI/ML:** LangChain + Ollama (Llama 3, Mistral, CodeLlama)
- **Vector DB:** Qdrant
- **Monitoring:** Custom API
- **Infrastructure:** Docker (5 containers)

## Documentation Structure

- **Platform** - Getting started, architecture, containers, databases
- **API** - REST API reference and endpoint documentation

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## License

MIT License - see [LICENSE](./LICENSE) file for details

## Support

- 📧 Email: support@novatek.com
- 🐙 GitHub: https://github.com/novatek-dev
- 📖 Docs: https://docs.novatek.com

