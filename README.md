# ⚙️ System Preferences

> Customize your zOS experience

Part of the [zOS Apps](https://github.com/zos-apps) ecosystem.

## Installation

```bash
npm install github:zos-apps/system-preferences
```

## Usage

```tsx
import App from '@zos-apps/system-preferences';

function MyApp() {
  return <App />;
}
```

## Package Spec

App metadata is defined in `package.json` under the `zos` field:

```json
{
  "zos": {
    "id": "ai.hanzo.systempreferences",
    "name": "System Preferences",
    "icon": "⚙️",
    "category": "system",
    "permissions": ["system"],
    "installable": true
  }
}
```

## Version

v4.2.0

## License

MIT © Hanzo AI
