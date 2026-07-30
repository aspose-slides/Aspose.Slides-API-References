---
title: "System::Net::Security"
second_title: Aspose.Slides pro C++ API referenci
description: 
type: docs
weight: 716
url: /cs/system.net.security/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Obsahuje metody pro předávání přihlašovacích údajů přes stream. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to může vést k běhovým chybám a/nebo chybám aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [SslStream](./sslstream/) | Stream, který používá protokol SSL k ověření serveru a případně klienta. |
## Výčty

| Výčet | Popis |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Specifické ověřovací příznaky pro WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Vyjmenovává chyby politiky SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Vyjmenovává šifrovací politiky. |
## Definice typů

| Definice typu | Popis |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Delegát uživatele používaný k ověření vzdáleného certifikátu SSL. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Delegát uživatele používaný k výběru lokálního certifikátu SSL. |