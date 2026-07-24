---
title: GetCredential()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt Anmeldeinformationen für die angegebene URI und den Authentifizierungstyp zurück.
type: docs
weight: 92
url: /de/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) Methode


Gibt Anmeldeinformationen für die angegebene URI und den Authentifizierungstyp zurück.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die URI. |
| authenticationType | [String](../../../system/string/) | Der Authentifizierungstyp. |

## NetworkCredential::GetCredential(String, int32_t, String) Methode


Gibt Anmeldeinformationen für den angegebenen Hostnamen, Port und Authentifizierungstyp zurück.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | [String](../../../system/string/) | Der Hostname. |
| port | **int32_t** | Die Portnummer. |
| authenticationType | [String](../../../system/string/) | Der Authentifizierungstyp. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [NetworkCredential](../)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)