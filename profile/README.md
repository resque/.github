# Resque

<a href="https://github.com/resque">
<img alt="Resque logo" align="right" width="192" height="192" hspace="30" src="https://logos.galtzo.com/assets/images/resque/avatar-192px.png">
</a>

[![Ruby Users Forum][ruby-forum-img]][ruby-forum]
[![Live Chat on Discord][discord-img]][discord]

The Resque org develops Resque and related libraries for Ruby and PHP.

Resque is Redis-backed background job infrastructure with a long history in Ruby applications.

## Community And Support

Use [Ruby Users Forum][ruby-forum] for longer support threads and maintenance
coordination. [Discord][discord] is available for live coordination. Individual resque org projects may also have GitHub Discussions enabled, or have additional or preferred ways to contact maintainers.

### Financial Support

Support Resque through [Open Collective][fund] or [thanks.dev][thanks].

## Projects

| Project | Description | Downloads | Funding |
| --- | --- | --- | --- |
| [resque](https://github.com/resque/resque) | Redis-backed Ruby library for creating and running background jobs. | [![resque][rd-resque-img]][rd-resque] | [Open Collective][fund] / [thanks.dev][thanks] |
| [resque-scheduler](https://github.com/resque/resque-scheduler) | Lightweight job scheduling system for Resque. | [![resque-scheduler][rd-resque-scheduler-img]][rd-resque-scheduler] | [Open Collective][fund] / [thanks.dev][thanks] |
| [resque-heroku-signals](https://github.com/resque/resque-heroku-signals) | Heroku process signal compatibility for Resque. | [![resque-heroku-signals][rd-resque-heroku-signals-img]][rd-resque-heroku-signals] | [Open Collective][fund] / [thanks.dev][thanks] |
| [resque-pool](https://github.com/resque/resque-pool) | Fork and manage pools of Resque workers. | [![resque-pool][rd-resque-pool-img]][rd-resque-pool] | [Open Collective][fund] / [thanks.dev][thanks] |
| [resque-unique_at_runtime](https://github.com/resque/resque-unique_at_runtime) | Runtime uniqueness enforcement for jobs. | [![resque-unique_at_runtime][rd-resque-unique-at-runtime-img]][rd-resque-unique-at-runtime] | [Open Collective][fund] / [thanks.dev][thanks] |
| [resque-unique_in_queue](https://github.com/resque/resque-unique_in_queue) | Queue-time uniqueness enforcement for jobs. | [![resque-unique_in_queue][rd-resque-unique-in-queue-img]][rd-resque-unique-in-queue] | [Open Collective][fund] / [thanks.dev][thanks] |
| [resque-unique_by_arity](https://github.com/resque/resque-unique_by_arity) | Job uniqueness based on argument arity. | [![resque-unique_by_arity][rd-resque-unique-by-arity-img]][rd-resque-unique-by-arity] | [Open Collective][fund] / [thanks.dev][thanks] |
| [redis-namespace](https://github.com/resque/redis-namespace) | Adds namespaced Redis keys through `Redis::Namespace`. | [![redis-namespace][rd-redis-namespace-img]][rd-redis-namespace] | [Open Collective][fund] / [thanks.dev][thanks] |
| [resque-web](https://github.com/resque/resque-web) | Rails-based web interface to Resque. | [![resque-web][rd-resque-web-img]][rd-resque-web] | [Open Collective][fund] / [thanks.dev][thanks] |
| [resque-lonely_job](https://github.com/resque/resque-lonely_job) | Resque job uniqueness helper. | [![resque-lonely_job][rd-resque-lonely-job-img]][rd-resque-lonely-job] | [Open Collective][fund] / [thanks.dev][thanks] |
| [php-resque](https://github.com/resque/php-resque) | Resque-style background jobs for PHP. | - | [Open Collective][fund] / [thanks.dev][thanks] |

Fun fact: the Resque project is now 16+ years old, and is still in use by many companies and projects.

[ruby-forum]: https://www.rubyforum.org/tag/resque
[ruby-forum-img]: https://img.shields.io/discourse/topics?server=https%3A%2F%2Fwww.rubyforum.org&style=flat&logo=discourse&label=Ruby%20Users%20Forum
[discord]: https://discord.gg/3qme4XHNKN
[discord-img]: https://raster.shields.io/discord/1373797679469170758?style=flat&logo=discord&label=Discord
[fund]: https://opencollective.com/resque
[thanks]: https://thanks.dev/u/gh/resque
[rd-resque]: https://bestgems.org/gems/resque
[rd-resque-img]: https://img.shields.io/gem/rd/resque.svg
[rd-resque-scheduler]: https://bestgems.org/gems/resque-scheduler
[rd-resque-scheduler-img]: https://img.shields.io/gem/rd/resque-scheduler.svg
[rd-resque-heroku-signals]: https://bestgems.org/gems/resque-heroku-signals
[rd-resque-heroku-signals-img]: https://img.shields.io/gem/rd/resque-heroku-signals.svg
[rd-resque-pool]: https://bestgems.org/gems/resque-pool
[rd-resque-pool-img]: https://img.shields.io/gem/rd/resque-pool.svg
[rd-resque-unique-at-runtime]: https://bestgems.org/gems/resque-unique_at_runtime
[rd-resque-unique-at-runtime-img]: https://img.shields.io/gem/rd/resque-unique_at_runtime.svg
[rd-resque-unique-in-queue]: https://bestgems.org/gems/resque-unique_in_queue
[rd-resque-unique-in-queue-img]: https://img.shields.io/gem/rd/resque-unique_in_queue.svg
[rd-resque-unique-by-arity]: https://bestgems.org/gems/resque-unique_by_arity
[rd-resque-unique-by-arity-img]: https://img.shields.io/gem/rd/resque-unique_by_arity.svg
[rd-redis-namespace]: https://bestgems.org/gems/redis-namespace
[rd-redis-namespace-img]: https://img.shields.io/gem/rd/redis-namespace.svg
[rd-resque-web]: https://bestgems.org/gems/resque-web
[rd-resque-web-img]: https://img.shields.io/gem/rd/resque-web.svg
[rd-resque-lonely-job]: https://bestgems.org/gems/resque-lonely_job
[rd-resque-lonely-job-img]: https://img.shields.io/gem/rd/resque-lonely_job.svg
