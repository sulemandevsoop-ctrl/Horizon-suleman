# Horizon-suleman

Shopify theme for [horizon-suleman.myshopify.com](https://horizon-suleman.myshopify.com).

## Setup

```bash
cd /Users/forsale/Documents/GitHub/Horizon-suleman
nvm use
npm install -g @shopify/cli @shopify/theme
shopify auth login
```

## Theme workflow

```bash
shopify theme pull -e store   # download live theme
shopify theme dev -e store      # local dev + hot reload
```

Store and environment are configured in `shopify.theme.toml`.
