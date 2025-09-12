# Standard Money Documentation

This is a Mintlify documentation site for the Standard Money protocol, built using the Mintlify starter kit and customized with Standard Money-specific content and styling.

## About Standard Money

Standard Money is a synthetic dollar protocol built on BSC (Binance Smart Chain) that creates USDsd, a synthetic, collateralized version of Tether. The protocol maintains USDsd's peg through sophisticated delta-neutral hedging mechanisms and basis trading strategies.

## Documentation Structure

The documentation is organized into three main sections:

### Overview

- **Getting Started**: Introduction and quickstart guide
- **How USDsd Works**: Technical explanations of USDsd mechanics
- **Protocol Revenue**: How the protocol generates and distributes revenue

### User Guides

The User Guides section provides comprehensive guidance for protocol users. The Getting Started section covers overview, minting, staking, and position management, while Advanced Topics delves into hedging systems and risk management strategies.

### Resources

The Resources section contains essential reference materials including Key Addresses with contract addresses and key information, Security & Trust documentation covering trust assumptions, backing/custody security, and reserve fund details, and Support resources including FAQ and terms of service.

## Key Features

- **Enhanced Styling**: Custom CSS with Standard Money's brand colors and improved visual design
- **Comprehensive Content**: Detailed documentation covering all aspects of the protocol
- **Interactive Components**: Accordions, cards, and other interactive elements

The documentation features responsive design optimized for all device sizes and includes automatic dark mode detection and styling for enhanced user experience.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Customization

### Colors

The site uses Standard Money's brand colors with primary blue at `#2e20de`, light blue at `#4c3ce8`, and dark blue at `#1a0fb8` to maintain brand consistency throughout the documentation.

### Styling

Custom styles are defined in `styles.css` and include enhanced card styling with gradients, improved accordion design, custom table styling, enhanced button and link styling, and responsive design improvements to ensure optimal user experience across all devices.

### Content

All content is written in MDX format and includes interactive components like Cards and Accordions, code blocks with syntax highlighting, tables and lists, alerts and notes, and links to external resources for comprehensive information delivery.

## Publishing

Install the GitHub app from your [Mintlify dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to automatically deploy changes when you push to the default branch.

## Content Sources

The documentation content is based on the Standard Money protocol, specifically covering key contract addresses and BSC deployment, protocol architecture and design principles, risk documentation and security model, and revenue mechanisms and distribution strategies.

## Need Help?

### Troubleshooting

If your dev environment isn't running, run `mint update` to ensure you have the most recent version of the CLI. If a page loads as a 404, make sure you are running in a folder with a valid `docs.json` configuration file.

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
- [Standard Money Telegram Chat](https://t.me/StandardMoneyChat)

For additional support, you can reach out through [Standard Money X (Twitter)](https://x.com/StandardMoney_) or [Standard Money News](https://t.me/StandardMoneyNews) for the latest updates and announcements.

## License

This documentation site is based on the Mintlify starter kit and is customized for the Standard Money protocol. Please refer to the original Mintlify license for terms and conditions.
