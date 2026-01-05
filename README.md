# StealthLynk LLC Website

Professional company visit card website for StealthLynk LLC.

## Structure

```
├── index.html          # Main website page
└── images/
    ├── background.png  # Parallax background
    ├── developpers.png # Development team image
    └── storage.png     # Server infrastructure image
```

## Deployment

This website is served from the StealthCloud server at the root path (`/`).

Copy the contents to the server's `public` directory:

```bash
scp -r * user@server:/opt/photolynk/public/
```

## Design

- Black/white/grey professional color scheme
- No logins, registrations, or data collection
- Parallax background effect
- Mobile responsive
- Semi-transparent cards with backdrop blur

## Company

StealthLynk LLC  
Wyoming, USA
