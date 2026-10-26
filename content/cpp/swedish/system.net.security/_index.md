---
title: "System::Net::Security"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 716
url: /sv/system.net.security/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Innehåller metoderna för att överföra autentiseringsuppgifter över en ström. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [SslStream](./sslstream/) | En ström som använder SSL-protokollet för att autentisera servern och valfritt klienten. |

## Enum

| Enum | Beskrivning |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest-specifika autentiseringsflaggor. |
| [SslPolicyErrors](./sslpolicyerrors/) | Enumererar policyfel för SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Enumererar krypteringspolicyer. |

## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | En användardelegat som används för att verifiera fjärr-SSL-certifikatet. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | En användardelegat som används för att välja lokalt SSL-certifikat. |