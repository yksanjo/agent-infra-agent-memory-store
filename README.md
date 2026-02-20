# @agent-infra/agent-memory-store

**Distributed Memory Store for AI Agent State**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Features

- 🔧 Production-ready implementation
- 📦 Easy to integrate  
- 🧪 Comprehensive test coverage
- 📚 Well-documented API
- 🚀 Performance optimized

## Installation

```bash
pip install @agent-infra/agent-memory-store
```

## Quick Start


```python
from agent_infra_agent_memory_store import AgentMemoryStore

instance = AgentMemoryStore()
await instance.initialize()
result = await instance.execute({"task": "your task"})
print(result)
```


## API Reference

### `AgentMemoryStore`

Main class for agent memory store functionality.

#### Methods

- `initialize()` - Initialize the component
- `execute(input)` - Execute main logic  
- `configure(config)` - Update configuration

## Testing

```bash
pytest
```

## License

MIT - See [LICENSE](LICENSE) for details

## Support

- Issues: https://github.com/yksanjo/agent-infra-agent-memory-store/issues
- Discussions: https://github.com/yksanjo/agent-infra-agent-memory-store/discussions
