# Compalyze MCP — Developer Docs

[Compalyze](https://compalyze.co.jp) の MCP サーバー（`https://mcp.compalyze.co.jp`）の開発者向けドキュメントです。
法人番号ベースで日本企業を広く収録し、登記・財務・関係・役員などのデータを Claude などの AI エージェントから扱えます。

📖 **ドキュメント:** https://ryuji-s.github.io/compalyze-mcp-docs/
🌐 **Web アプリ:** https://compalyze.co.jp
🔑 **APIキー発行 / ダッシュボード:** https://mcp.compalyze.co.jp

## クイックスタート

```bash
claude mcp add compalyze https://mcp.compalyze.co.jp/mcp \
  --transport http \
  --header "Authorization: Bearer cpz_xxxxxxxxxxxxxxxx"
```

## ツール

`search_companies` / `discover_companies` / `search_timeline` /
`get_company_register` / `get_company_officers` / `get_company_financials` /
`get_company_kpis` / `get_company_events` / `get_company_news` /
`get_company_relations` / `report_data_issue`

詳細は [ドキュメントサイト](https://ryuji-s.github.io/compalyze-mcp-docs/) を参照してください。

---

運営：株式会社Compalyze ｜ https://compalyze.co.jp
