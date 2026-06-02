# terraphim-config-persistence

Configuration and persistence-layer crates for Terraphim AI, extracted from the
`terraphim-ai` monorepo (Gitea #1910 polyrepo split):

- `terraphim_config` -- role-based configuration management
- `terraphim_persistence` -- multi-backend storage abstraction
- `terraphim_settings` -- device/server settings
- `terraphim_atomic_client` -- Atomic Data integration
- `terraphim_onepassword_cli` -- 1Password CLI integration

Depends on terraphim-core via the Terraphim private Cargo registry (`terraphim`
org). Published to the same registry.
