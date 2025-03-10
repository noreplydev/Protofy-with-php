<h3 align="center"> 
<image height="50" src="https://raw.githubusercontent.com/Protofy-xyz/Protofy/assets/logo-protofy.png">
</h3>

<h4 align="center">
  <a href="https://github.com/protofy-xyz/protofy/graphs/contributors">
    <img src="https://img.shields.io/github/contributors-anon/protofy-xyz/protofy?color=yellow&style=flat" alt="contributors" style="height: 20px;">
  </a>
  <a href="https://opensource.org/licenses/mit">
    <img src="https://img.shields.io/badge/mit-blue.svg?style=flat&label=license" alt="license" style="height: 20px;">
  </a>
  <a href="https://discord.gg/VpeZxMFfYW">
    <img src="https://img.shields.io/badge/discord-7289da.svg?style=flat&logo=discord" alt="discord" style="height: 20px;">
  </a>
</h4>


<p align="center">The fastest way to create and scale agent networks</p> 
We believe that AI agents need to be more than models. Modern products are powered by a myriad of programs and devices, and those programs and devices are also agents and should be able to communicate with each other. Protofy is the framework that allows humans, AIs and services to talk to each other.

With Protofy, any doer can build agent networks that helps them create, iterate and scale digital products and services. In hours.

The Agent Network provides a way for agents to discover, understand, and interact with each other without human intervention. Users can incorporate their own code and make it available as an agent in the network.

Our agent definition protocol, network, and platform are open source to foster a community of creators who contribute examples, templates, and connectors.

Check the [getting started](docs/getting-started.md) guide to run Protofy on your computer, directly with npm or using docker.

## 👨‍💻 Extendable and developer friendly CMS
 
https://github.com/Protofy-xyz/Protofy/assets/5052882/e5c3f0fa-5b76-4c8e-bb4f-6a2c588ec53c

## 🤖 Ai Assisted

https://github.com/Protofy-xyz/Protofy/assets/5052882/4b7da628-a55e-4904-81c3-6aca23eb776d

Get help and code from integrated ChatGPT with automatic context transfer

## 😎 Realtime interactive diagrams that edit Javascript / Typescript code

![codeedit](https://github.com/Protofy-xyz/Protofy/assets/5052882/98c071cf-c934-4891-90e7-ad2d05602aad)

Edit any Javascript or typescript code using visual programming or traditional code

## 🧰 Connected devices (IoT) support for ESP32 based on ESPHome 

![devices-package](https://github.com/Protofy-xyz/Protofy/blob/assets/device/device-1.gif?raw=true)

Program, deploy and manage connected devices and IoT networks visually, in minutes. 

## 📦 Included packages

- `Protoflow` LowCode interactive diagram system for Javascript and Typescript
- `VisualUI` What you see is what you get (wysiwyg) for react, like FlutterFlow but for react
- `Protolib` Protofy Framework on top of react, express and tamagui
- `Express` API system based on NodeJS (With automatic CRUD creation)
- `Aedes` mqtt server
- [Tamagui](https://tamagui.dev) 🪄
- [Solito](https://solito.dev) for cross-platform navigation
- `Expo SDK`
- `Next.js`
- `Expo Router`
- `Many more things!`

## 🗂️ Folder layout
The project has two main folders: 

- `apps` 
  - `expo` (native)
  - `next` (web)
  - `api` (express API to create the web or app)
  - `core` (mqtt, mangement apis, authentication, ...)

- `packages` shared packages across apps
  - `ui` includes your custom UI kit that will be optimized by Tamagui
  - `app` you'll be importing most files from `app/`
    - `bundles`
      - `custom` the custom bundle, put here your custom pages, components, apis, etc. The admin panel reads and writes on this bundle.
  - `protolib` Protofy react library with high level widgets and functions to bootstrap the web/app creation
  - `protoflow` Protofy react library to draw js/ts/jsx/tsx as diagrams
  - `visualui` Protofy react library to do WYSIWYG in react
  - `protodevice` Protofy integration with ESPHome for IoT and device management

You can add other folders inside of `packages/` if you know what you're doing and have a good reason to.

## 🚀 Getting Started
https://github.com/Protofy-xyz/Protofy/assets/99766455/930e5eb5-abab-4956-8ae2-31f0c284aa31

First steps? Check the [getting started](docs/getting-started.md) guide.

## 📚 Documentation
You already know the basics? Check these amazing docs to learn more:

- [Getting Started](docs/getting-started.md)
- [Workspace, What is?](docs/workspace.md)
- [Protofy packages](docs/packages.md)
  - [Protolib](docs/protolib.md)
- [Extending Protofy](docs/extending-protofy.md)

## 🧭 Roadmap
Coming  soon...

## 📜 License
Check out the [LICENSE](LICENSE.md) file for details.

## 🙌 Contributing and Community
We would love to develop Protofy together with our community! Best way to get started is to select any issue. If you would like to contribute, please review our [Contributing Guide]() for all relevant details.

## 🆘 Getting Help
The first point of call should be our [Discord]("https://discord.gg/VpeZxMFfYW"). Ask your questions about bugs or specific use cases, and someone from the core team will respond. Or, if you prefer, open an issue on our GitHub repo.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Protofy-xyz/Protofy&type=Date)](https://star-history.com/#Protofy-xyz/Protofy&Date)

## 🙏 Credits and References
Many thanks [@natew](https://twitter.com/natebirdman) for creating the original starter and to [@FernandoTheRojo](https://twitter.com/fernandotherojo) for the Solito starter monorepo which the original [@natew](https://twitter.com/natebirdman) starter was forked from. Check out Fernando Rojo his [talk about using expo + next together at Next.js Conf 2021](https://www.youtube.com/watch?v=0lnbdRweJtA).

Many thanks also to [@OttoWinter](https://github.com/OttoWinter) for creating [ESPHome](https://github.com/esphome) project. We want also to thank [Choly Knight](https://cholyknight.com/) for being our main inspiration creating Protofito concept based on her Robot Plush design. 

