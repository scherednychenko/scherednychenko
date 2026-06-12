### Hi, I'm Sergiy 👋

**Performance Engineering & AI Quality Testing for product teams** — load & stress audits, LLM evaluations, EU AI Act readiness.

📍 Croatia &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/sergiycherednychenko/) &nbsp;·&nbsp; 🌐 [professional-qa-services.com](https://www.professional-qa-services.com/english/)

---

## 🚀 Featured — ShopLite Load Tests: one scenario, six tools

The same e-commerce journey (**browse → add-to-cart → checkout**), implemented across five load-testing tools (plus a frontend Core Web Vitals one) — each a **one-command Dockerized demo** that spins up a mock backend,
runs the test, and produces an HTML report.

![ShopLite — one scenario, six tools (five load + Core Web Vitals)](assets/shoplite-tools-comparison.png)

| Tool | Language / DSL | SLOs as | Report | Repo |
|---|---|---|---|---|
| Apache JMeter | XML + Groovy | Assertions | HTML dashboard | [ShopLite-load-tests](https://github.com/scherednychenko/ShopLite-load-tests) |
| Grafana k6 | JavaScript | Thresholds | HTML report | [ShopLite-load-tests-k6](https://github.com/scherednychenko/ShopLite-load-tests-k6) |
| Locust | Python | Code-level checks | Built-in HTML | [ShopLite-load-tests-locust](https://github.com/scherednychenko/ShopLite-load-tests-locust) |
| Gatling | Scala DSL | Assertions | HTML charts | [ShopLite-load-tests-gatling-scala](https://github.com/scherednychenko/ShopLite-load-tests-gatling-scala) |
| Gatling | Java DSL | Assertions | HTML charts | [ShopLite-load-tests-gatling-javaDSL](https://github.com/scherednychenko/ShopLite-load-tests-gatling-javaDSL) |
| sitespeed.io | JavaScript | Budgets | HTML + Grafana | [ShopLite-ui-perf](https://github.com/scherednychenko/ShopLite-ui-perf) |
| **Observability** | InfluxDB + Grafana | — | Live dashboards | [ShopLite-observability](https://github.com/scherednychenko/ShopLite-observability) |

Each repo also ships a documented test strategy — SLIs/SLOs, test cadence, environment
constraints, and how performance testing fits into an Agile team's rituals.

> 💡 **The script is the easy part.** The real value is knowing *what* to test, shaping the load model, reading the results, and turning them into a go/no-go call — judgment a demo can't capture.

---

### 🧰 What I work on
- **Performance & load testing** — JMeter · k6 · Locust · Gatling · sitespeed.io · Grafana + InfluxDB dashboards
- **AI quality testing** — LLM evaluations, red teaming, EU AI Act readiness
- **Test strategy** — SLIs/SLOs, CI integration, reporting that non-engineers can read
