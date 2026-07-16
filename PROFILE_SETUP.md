# GitHub profile repository setup

GitHub displays this repository's root `README.md` on your account profile only when:

- the repository is public;
- the repository name exactly matches your GitHub username: `tagadearpit`;
- `README.md` is stored in the repository root.

## Publish this version

Extract the ZIP into your existing local `tagadearpit` repository and replace the old files.

```bash
git add .
git commit -m "Rebuild professional GitHub profile"
git push origin main
```

## Files included

```text
README.md
PROFILE_SETUP.md
LICENSE
.gitignore
assets/profile-header.svg
```

## Design decisions

This profile intentionally avoids third-party GitHub statistics cards, streak services, contribution snakes, remote typing animations, and telemetry images. Those services can be rate-limited, unavailable, or visually inconsistent.

The only visual asset is stored locally in `assets/profile-header.svg`, which makes the profile more reliable and easier to maintain.

## Updating links

Project and contact links are stored directly in `README.md`. Update them whenever a deployment URL or repository name changes.

Current deployment links:

- Portfolio: `https://my-portfolio-snowy-sigma-18.vercel.app/`
- Monika AI: `https://monika-ai-0jpf.onrender.com`
- Neosis: `https://neosis-static-site.onrender.com`

## Privacy

The profile includes public professional contact channels only. It intentionally does not publish a phone number or private credentials.
