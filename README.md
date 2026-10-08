### Hi, I'm Tyler

I've spent three decades where databases meet the people who use them: building developer communities, telling product stories, and explaining why the internals matter. These days I'm a Storyteller at [ClickHouse](https://github.com/ClickHouse) in Amsterdam.

```sql
DESCRIBE tyler;
```

| field        | value                                                        |
|--------------|--------------------------------------------------------------|
| `now`        | Storyteller @ ClickHouse                                     |
| `previously` | Macrometa · Hasura · Fauna · Elastic · Basho · many others   |
| `focus`      | databases, distributed systems, community                    |
| `speaks_at`  | conferences, meetups, release calls, wherever you'll have me |

### Things I've built lately

- **[world-summit-ai-from-humans-to-agents](https://github.com/tylerhannan/world-summit-ai-from-humans-to-agents)**: the demo from my World Summit AI 2026 talk, "From Humans to Agents". Claude agents query ClickHouse over MCP, with every run traced and evaluated in Langfuse.
- **[kill-your-dashboards](https://github.com/tylerhannan/kill-your-dashboards)**: a synthetic iGaming dataset for ClickHouse, generated entirely in SQL (up to 10B bets), with five problems planted in it that no dashboard would ever surface.
- **[coldrun](https://github.com/tylerhannan/coldrun)**: a small columnar SQL engine in Rust, built as an AI experiment against ClickBench `hits`. Very much a toy.
- **[redpanda-demo](https://github.com/tylerhannan/redpanda-demo)**: streaming clickstream events from Redpanda Serverless into ClickHouse Cloud via ClickPipes.

### Talks worth your time

```sql
SELECT *
FROM talks
WHERE highlight IS NOT NULL
ORDER BY highlight
LIMIT 6;
```

| title | event |
|-------|-------|
| [Open Source as Stained Glass](https://www.youtube.com/watch?v=dBDu0NHKmWI) | ClickHouse Open House 2026 (keynote) |
| [Do Metrics Matter?](https://www.youtube.com/watch?v=8mHSNPYy004) | SREday London 2026 (keynote) |
| [ML, Vectors, and Philosophy: Oh my!](https://www.youtube.com/watch?v=1Qqd2JEsSeU) | Latency Conference 2025 |
| [My Favourite ClickHouse Features](https://www.youtube.com/watch?v=6mCahEIDwFc) | ClickHouse Singapore Meetup 2024 |
| [Learning Databases and Learning Languages](https://www.youtube.com/watch?v=ZICoTYUPFq4) | ClickHouse Community Meetup 2023 |
| [Medieval Art, Collective Intelligence, and Language Abuse](https://www.youtube.com/watch?v=MboWxOKP4-Y) | Monktoberfest 2013 |

### Say hi

[LinkedIn](https://www.linkedin.com/in/tylerhannan/) · [X / Twitter](https://twitter.com/tylerhannan)
