# Serene Spa Booking Prototype

Interactive single-page prototype for Spa booking and daily operations.

## Run locally

Open `index.html` in a modern browser. Demo changes are stored in that browser's local storage. Use **Đặt lại dữ liệu** in the sidebar to reset the sample data.

## Publish with GitHub Pages

The repository currently uses the `main` branch and the prototype entry point is `/index.html`.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. After GitHub finishes publishing, the site URL should be `https://phunguyenvan-oss.github.io/spa-booking/`.

This repository is private. GitHub Pages availability and visitor access depend on the repository owner's GitHub plan and Pages settings. Do not put real customer data in this demo.

## Wheel design alignment

The prototype UI has been updated using Wheel Foundation semantic values inspected through Figma MCP:

- Page background: `alias color/background/faded` (`#f0f3f5`)
- Surface: `alias color/background/default` (`#ffffff`)
- Main content: `alias color/content/default` (`#111827`)
- Secondary content: `alias color/content/neutral` (`#4b5563`)
- Primary action: `alias color/content/accent` / `alias color/background/accent` (`#2463eb`)
- Borders: `alias color/border/default` and `alias color/border/strong`
- Typography: Inter; operational UI uses 14px/20px body sizing
- Spacing follows the Wheel scale (4, 8, 12, 16, 24, 32px); controls and surfaces use compact 6–12px radii.

This is a standalone HTML prototype. Its controls are coded in HTML/CSS and are visually aligned to Wheel rules; they are not live Figma component instances or React components from a Wheel code package. The Spa-specific workflows and information architecture remain tailored to booking operations.

## Prototype scope

Today workspace, appointment calendar and list, booking creation and rescheduling, customer profiles, services and packages, staff/resources, service status transitions, checkout, package-session deduction, transactions, and sample reports.

All content is mock data; this is not a production system.
