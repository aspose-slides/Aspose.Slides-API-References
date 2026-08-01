---
title: "System::Net::Security"
second_title: Aspose.Slides voor C++ API Referentie
description: 
type: docs
weight: 716
url: /nl/system.net.security/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Bevat de methoden voor het doorgeven van referenties via een stream. Objecten van deze klasse mogen alleen worden gealloceerd met de functie [System::MakeObject()](../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze aan functies door te geven als argument. |
| [SslStream](./sslstream/) | Een stream die het SSL-protocol gebruikt om de server te authenticeren en optioneel de client. |
## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest-specifieke authenticatie-vlaggen. |
| [SslPolicyErrors](./sslpolicyerrors/) | Somt de beleidsfouten van SSL op. |
| [EncryptionPolicy](./encryptionpolicy/) | Somt de encryptie-beleidsregels op. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Een gebruikers-delegate die wordt gebruikt om een extern SSL-certificaat te verifiëren. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Een gebruikers-delegate die wordt gebruikt om een lokaal SSL-certificaat te selecteren. |