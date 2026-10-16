## Roman Lesnikov

Full-stack engineer, 25 years. Paphos, Cyprus — remote since 2005.

I build cross-platform products end to end: one React and TypeScript codebase that ships as a Next.js web app and as native iOS and Android apps on Expo, with a PHP and MySQL backend underneath. On the product I work on now, roughly 60% of the repository's commits are mine.

For the last two years a large part of that has been AI in production — agent chat with streaming and tool calls, an agent runtime, LLM-as-judge evaluation, and a versioned agent skill registry shared across Claude Code, Cursor and Codex so the whole team works the same way.

**React Native · Expo · React 19 · Next.js · TypeScript · PHP · MySQL · Redis · Node.js**

### Open source

- [**unacms/UNA**](https://github.com/unacms/UNA/pulls?q=is%3Apr+author%3Aromanlesnikov+is%3Amerged) — NEO, the cross-platform client I'm the main author of, lives inside the UNA CMS repository, so my day-to-day work lands there as merged pull requests: the AI agent layer (chat threads, tool calls, safe MySQL tools, an operator agent), the shared SSR page cache, cross-list state for likes and comments, the editor.
- [**expo-envelope-crypto**](https://github.com/romanlesnikov/expo-envelope-crypto) — password-protected envelope encryption for React Native and the web: AES-256-GCM, a wrapped data key, and a KDF iteration count you can raise without locking existing users out.
- [**uniwind-style-probe**](https://github.com/romanlesnikov/uniwind-style-probe) — checks that Tailwind breakpoint and platform variants survive uniwind's native compilation, without building the app or touching a device.
- [**uni-stack/uniwind#668**](https://github.com/uni-stack/uniwind/issues/668) — found that the same root cause behind leaking `ios:`/`android:` variants also stripped responsive breakpoints: with tailwindcss merging `@media` blocks, every `sm:`/`lg:`/`xl:` class after the first compiled to `minWidth: 0` and applied at every width. Fixed in [v1.12.1](https://github.com/uni-stack/uniwind/releases/tag/v1.12.1).

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/roman-lesnikov-5a215b76)
