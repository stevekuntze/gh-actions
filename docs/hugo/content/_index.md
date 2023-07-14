---
title: Index
---

# Dyps

In dem Dokument wird die Dynamische Preissteuerung beschrieben.

## Reports

- [Test Report](/reports/all-test-results/index.html)
- [Test Coverage](/reports/coverage/index.html)
- [Code Style Report](/reports/detekt/main.html)

<!-- - [Sicherheitsreport Abhängigkeiten](/reports/dependency-check-report.html) -->
<!-- - [Aktualisierbare Abhängigkeiten](/reports/dependencyUpdates.txt) -->

**WICHTIG**: Die Abhängigkeiten sind größtenteils durch SpringBoot gemanaged und deshalb nicht immer auf dem neusten
Stand.

## Links

- Bitbucket: https://bitbucket.otto.de/projects/SP/repos/dyps/browse
- Jira: https://jira.scm.otto.de/projects/DYPSSTRG
- AWS: https://adfs.ottogroup.com/adfs/ls/IdpInitiatedSignOn.aspx?loginToRp=urn:amazon:webservices
- Firewall Login: https://fwauth.ov.otto.de/connect/PortalMain
- Monitoring: https://grafana.dyps.org
- Kubernetes https://dashboard.dyps.org
- Keycloak (Authentifizierung) https://auth.alsterfleet.org
- Jenkins (Build) https://jenkins.dyps.org

## Systeme

- Die DyPs-Steuerung ist primär nur noch über das [HändlerPortal](https://start.retail-connect.otto.de/) zu erreichen.
- Die Integrationsumgebung der DyPs-Steuerung ist über die
  [Demo-Stage des Händlerportals](https://start.retail-connect-demo.otto.de/) zu erreichen.
- Die Adresse [integration.dyps.org](https://integration.dyps.org) leitet entsprechend auf Integration weiter.
- Die Adresse [dyps.org](https://dyps.org) leitet auf die Produktion weiter.
- Für die Entwicklung stehen weiterhin die [produktion](https://prod.dyps.org) und [integration](https://dev.dyps.org)
  zur Verfügung. Damit kann auch ohne OttoVPN getestet und gearbeitet werden.

## Repositories

Projektübersicht: https://bitbucket.scm.otto.de/projects/SP

### dyps

Enthält den Hauptteil der Anwendung einschließlich Infrastruktur

### SalesProduct

Enthält den Hauptteil der Anwendung SalesProduct einschließlich Infrastruktur

### Jenkins

Enthält den Jenkins Build-Server des SalesProduct-Teams.

### Jenkins_Dyps

Enthält den Jenkins Build-Server des Dyps-Teams.

### AwsCostMeter

Enthält einen Prometheus Exporter für die anfallenden AWS Kosten.

### PostgresS3Backup

Enthält den Docker Container zum Backup der Datenbank nach S3.
