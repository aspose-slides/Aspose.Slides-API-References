---
title: "System::Net::Security"
second_title: Aspose.Slides für C++ API Referenz
description: 
type: docs
weight: 716
url: /de/system.net.security/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Enthält die Methoden zum Übergeben von Anmeldeinformationen über einen Stream. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SslStream](./sslstream/) | Ein Stream, der das SSL-Protokoll verwendet, um den Server und optional den Client zu authentifizieren. |
## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest-spezifische Authentifizierungsflags. |
| [SslPolicyErrors](./sslpolicyerrors/) | Enumeriert die Richtlinienfehler von SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Enumeriert die Verschlüsselungsrichtlinien. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Ein Benutzer-Delegate, das zur Überprüfung des entfernten SSL-Zertifikats verwendet wird. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Ein Benutzer-Delegate, das zum Auswählen des lokalen SSL-Zertifikats verwendet wird. |