---
title: Remove()
second_title: Aspose.Slides für C++ API Referenz
description: Entfernt Netzwerkanmeldedaten für das angegebene URI-Präfix und den Authentifizierungstyp.
type: docs
weight: 53
url: /de/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) Methode

Entfernt Netzwerkanmeldedaten für das angegebene URI-Präfix und den Authentifizierungstyp.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Das URI-Präfix. |
| authenticationType | [String](../../../system/string/) | Der Authentifizierungstyp. |

## CredentialCache::Remove(String, int32_t, String) Methode

Entfernt Netzwerkanmeldedaten für den angegebenen Hostnamen, Port und Authentifizierungstyp.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | [String](../../../system/string/) | Der Hostname, dem die Anmeldedaten zugeordnet sind. |
| port | **int32_t** | Die Port-Nummer. |
| authenticationType | [String](../../../system/string/) | Ein Authentifizierungstyp. |

## Sieh auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [CredentialCache](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)