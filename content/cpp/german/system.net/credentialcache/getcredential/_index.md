---
title: GetCredential()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt Anmeldeinformationen für das angegebene URI-Präfix und den Authentifizierungstyp zurück.
type: docs
weight: 66
url: /de/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) Methode

Gibt Anmeldeinformationen für das angegebene URI-Präfix und den Authentifizierungstyp zurück.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Das URI-Präfix. |
| authenticationType | [String](../../../system/string/) | Ein Authentifizierungstyp. |

## CredentialCache::GetCredential(String, int32_t, String) Methode

Gibt Anmeldeinformationen für den angegebenen Hostnamen, den Port und den Authentifizierungstyp zurück.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | [String](../../../system/string/) | Der Hostname, dem die Anmeldeinformationen zugeordnet sind. |
| port | **int32_t** | Die Portnummer. |
| authenticationType | [String](../../../system/string/) | Der Authentifizierungstyp. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [NetworkCredential](../../networkcredential/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [CredentialCache](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)