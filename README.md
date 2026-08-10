# SAP RDP Security Learning Guide

A static reference site for learning SAP Responsible Design and Production (RDP) from an SAP Security perspective.

## Content

- SAP RDP architecture
- SAP BTP account hierarchy and security boundaries
- SAP BTP authentication
- Identity lifecycle, trust, and group mapping
- Roles and role collections
- SAP-delivered role matrix and proposed customer role collections
- Segregation-of-duties risks and mitigations
- Visual authorization model
- S/4HANA / ECC integration
- Integration security
- BTP destinations, Cloud Connector, service credentials, certificates, and audit logging
- Consultant security-design checklist
- Quick-reference cheat sheet
- Official SAP learning links

## Run locally

No build tooling is required.

Open `index.html` directly in a browser, or serve the directory with a simple local web server.

For example:

```powershell
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Suggested GitHub repository

`sap-rdp-security-guide`

## Deploy with GitHub Pages

1. Create a public repository named `sap-rdp-security-guide`.
2. Add the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

GitHub Pages will publish the site after the Pages deployment completes.

## Updating the guide

The site intentionally uses plain HTML/CSS/JavaScript so it is easy to update without a framework.

SAP cloud services change over time. Validate role names, security recommendations, and integration patterns against current SAP Help documentation before using this guide as a production design source.
