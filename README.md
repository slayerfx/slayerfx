# Louenn Penanc'hoat

Full stack developer.

I work mostly in PHP and Python. I contribute to the
[PHPOffice](https://github.com/PHPOffice) libraries — static analysis, continuous
integration, file reader fixes — and I build my own tools when nothing out there
does quite what I need.

## Projects

### [OneMoreRep](https://github.com/slayerfx/onemorerep) · [live demo](https://onemorerep.infinityfree.io)

Strength training site in PHP 8: exercise library, custom workout programs and a
daily energy expenditure calculator (Mifflin-St Jeor). MVC architecture written
without a framework, MySQL through PDO with prepared statements, PHPUnit tests.

### [SoundGrab](https://github.com/slayerfx/soundgrab)

SoundCloud downloader with a local web interface. FastAPI + yt-dlp, progress pushed
over Server-Sent Events, no build step and nothing loaded from a CDN. 36 tests, ruff
linting, CI on Windows and Linux.

## Open source

Eleven-week internship spent on the [PHPOffice](https://github.com/PHPOffice) PHP
libraries, May to July 2026 — **41 merged pull requests across five repositories**.

Most of it went into **[PhpProject](https://github.com/PHPOffice/PhpProject)**
(209 ★, 32 PRs):

- **Four file formats implemented, reading and writing** — Gnome Planner, MSPDI
  and ProjectLibre, plus an HTML writer rendering a Gantt chart.
- **PHPStan raised from level 1 to 6**, one level per pull request, alongside
  `declare(strict_types=1)` and typed signatures across the source.
- **CI migrated from Travis to GitHub Actions** — extended PHP matrix, PHPStan
  job, samples execution check, code coverage, Dependabot.
- **Documentation migrated** from Sphinx to MkDocs, then to ProperDocs.

The rest went to [PHPPresentation](https://github.com/PHPOffice/PHPPresentation)
(1.4k ★, 3 PRs — coverage under PHPUnit 10+, minimum version raised, a version
guard on `imagedestroy()`), [Common](https://github.com/PHPOffice/Common) (3 —
PHPStan up to level 7, PHPStan 2.x support, PHP 8.5 in the CI matrix),
[PHPWord](https://github.com/PHPOffice/PHPWord) (2 — PHP 8.5 support, a PHPUnit
constraint fixing the test suite) and [Math](https://github.com/PHPOffice/Math)
(1 — PHP 8.5 in the CI matrix).
