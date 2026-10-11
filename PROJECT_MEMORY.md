# gatsby-starter-decap-cms — пам'ять проєкту

## CI checkpoint — 2026-10-11

- Канонічний план завершення: [COMPLETION_PLAN_UK.md](COMPLETION_PLAN_UK.md).
- CI configuration source: `e91229e1f17e5f2e672292e2dcbf6353955958cf`; база `ce719fd5dc17d441048068960d4a662dc1b76a18`, гілка `ci/balance-github-codemagic-20261011`, [PR #2](https://github.com/ziko1/gatsby-starter-decap-cms/pull/2) stacked поверх `fix/reproducible-gatsby-build-20261008`.
- GitHub Linux зберігає наявний suite; feature push більше не дублює PR, tag/main перевірки збережено. Job timeout 20 хвилин, скасування застарілих запусків, npm download cache додано.
- Статус source/configuration: **PASS**. Поточне hosted виконання: **BLOCKED_ENVIRONMENT** до runner; тести/build на цьому SHA **NOT_RUN**. Зміна CI не підтверджує readiness застосунку.
- Доказ: [evidence/ci-balance-20261011.json](evidence/ci-balance-20261011.json), [інструкція CI](docs/CI_BALANCE_UK.md).
- Код застосунку, залежності й тести не змінено. Історичні PASS лишаються прив'язаними до їхніх SHA. Наступний documentation-only commit зберігає workflow bytes; не використовувати його SHA замість наведеного configuration source.
- Після відновлення provider execution потрібен actual hosted check перед рішенням про merge. Merge, deploy та нові платні ресурси не виконувалися.
