<a href="https://@taktikorg/possimus-repellat.sh/" target="_blank" rel="noopener">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/header.jpg" />
    <img alt="Bebop" src="./assets/header.jpg" />
  </picture>
</a>

<div align="center">
  <h1>Bebop</h1>
  <h3>No ceremony, just code.<br/> Blazing fast, typesafe binary serialization.</h3>

  <a href="https://github.com/taktikorg/possimus-repellat/blob/main/LICENSE.txt">
    <img alt="Apache License" src="https://img.shields.io/github/license/betwixt-labs/@taktikorg/possimus-repellat" />
  </a>
  <a href="https://discord.gg/jVfz9sMPWv">
    <img alt="Discord" src="https://img.shields.io/discord/1102669305537110036?color=7389D8&label&logo=discord&logoColor=ffffff" />
  </a>
  <br />
  <a href="https://twitter.com/andrewmd5">
    <img alt="Twitter" src="https://img.shields.io/twitter/url.svg?label=%40andrewmd5&style=social&url=https%3A%2F%2Ftwitter.com%2Fandrewmd5" />
  </a>
</div>

<br />

## Introduction


Bebop is a high-performance data interchange format designed for fast serialization and deserialization.


<table>
  <tr>
    <td>
      <pre lang="c">
        <code>
// Example Bebop Schema
struct Person {
  string name;
  uint32 age;
}
        </code>
      </pre>
    </td>
    <td>
      <pre lang="typescript">
        <code>
// Generated TypeScript Code
new Person({
    name: "Spike Spiegel",
    age: 27
}).encode();
        </code>
      </pre>
    </td>
  </tr>
  <tr>
    <td>Write concise and expressive schemas with Bebop's intuitive syntax.</td>
    <td>Using a generated class to persist data.</td>
  </tr>
</table>

It combines the simplicity of JSON with the efficiency of binary formats, delivering exceptional performance. In benchmarks, Bebop outperforms Protocol Buffers by approximately 10 times in both C# and TypeScript. Compared to JSON, Bebop is roughly 10 times faster in C# and about 5 times faster in TypeScript.

![Benchmark Graphs](https://user-images.githubusercontent.com/1297077/235745675-fc8a18e2-361f-4b7b-b9c9-47155e511b0a.png)

Bebop provides a modern, developer-friendly experience while ensuring top-notch performance. It is the ideal choice for any application that requires efficient data serialization, especially in performance-critical scenarios.

To explore the schema language and see examples of the generated code, check out the [playground](https://play.@taktikorg/possimus-repellat.sh/).

### Key Features

- 🧙‍♂️&nbsp; Supports [Typescript](https://docs.@taktikorg/possimus-repellat.sh/guide/getting-started-typescript/), [C#](https://docs.@taktikorg/possimus-repellat.sh/guide/getting-started-csharp/), [Rust](https://docs.@taktikorg/possimus-repellat.sh/guide/getting-started-rust/), C++, and more.
- 🐎&nbsp; Snappy DX - integrate `@taktikorg/possimus-repellatc` into your project with ease. Language support available in [VSCode](https://marketplace.visualstudio.com/items?itemName=betwixt.@taktikorg/possimus-repellat-lang).
- 🍃&nbsp; Lightweight - Bebop has zero dependencies and a tiny runtime footprint. Generated code is tightly optimized.
- 🌗&nbsp; RPC - build efficient APIs with [Tempo](https://docs.@taktikorg/possimus-repellat.sh/tempo/).
- ☁️&nbsp; Runs everywhere - browsers, serverless platforms, and on bare metal.
- 📚&nbsp; Extendable - write extensions for the compiler [in any language](https://docs.@taktikorg/possimus-repellat.sh/chords/what-are-chords/).

**👉 For more information, check out the [documentation](https://docs.@taktikorg/possimus-repellat.sh). 👈**

[_See You Space Cowboy_...](https://www.youtube.com/watch?v=u1UZHXB_r6g)
