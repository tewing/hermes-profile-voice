# hermes-profile-voice

Home voice assistant Hermes profile. Home Assistant's hermes_voice
integration calls it over the API server at `/p/voice/v1`. See
`distribution.yaml` and `SOUL.md`.

Exported from aaa's live `voice` profile (Hermes v0.23.0) on 2026-11-21.
Hermes installs the `hindsight` and `homeassistant` plugins the first time the
profile starts (a distribution can't ship plugins); this needs
`security.allow_lazy_installs`, which is on by default. `hindsight/config.json` sets context mode with a
low recall budget so voice turns stay fast.

Releases: bump `version:` in `distribution.yaml`; merging to `main` tags
`v<version>`. Deployments pin that tag.
