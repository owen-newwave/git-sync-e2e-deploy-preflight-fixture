# git-sync-e2e-deploy-preflight-fixture

Disposable, public asset host for the isolated deployment-preflight E2E validation
(ADR 0005/0006, Fase 6). Hosts a fictional Joomla-extension-shaped update package
and its update feed as GitHub Release assets, used only so the real
ExtensionManifestResolver HTTP path can be exercised end-to-end without touching any
real customer infrastructure or private repository. Safe to delete after validation.
