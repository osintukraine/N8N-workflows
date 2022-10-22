# n8n-workflows

Collection of [n8n.io](https://n8n.io/) workflows used by osintukraine.com.

### Workflows

- **RSS-to-Twitter-RU**
  Read `https://russia.osintukraine.com/index.xml` RSS feed periodically and
  post to Twitter
- **RSS-to-Twitter-UA**
  Read `https://ukraine.osintukraine.com/index.xml` RSS feed periodically and
  post to Twitter
- **telehunt**:
  Take Telegram aggregation from osintukraine.com
  [Inoreader](https://www.inoreader.com/) RSS feed, push posts to DeepL for
  translation, store posts in [Baserow](https://baserow.io/) instance and
  publish translation to Telegram
  [@telehunt_broadcast](https://t.me/telehunt_broadcast).

### How to use

Go to the top right three-dot menu in your `n8n` instance, select
`Import from file`, select the workflow `.json` file (e.g. `telehunt.json`).

The next step is to edit the credentials and customize the workflow for your
specific use case.
