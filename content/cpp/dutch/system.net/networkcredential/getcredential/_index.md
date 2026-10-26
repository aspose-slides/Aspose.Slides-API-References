---
title: GetCredential()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert referenties voor de opgegeven URI en het authenticatietype.
type: docs
weight: 92
url: /nl/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) methode

Retourneert referenties voor de opgegeven URI en het authenticatietype.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De URI. |
| authenticationType | [String](../../../system/string/) | Het authenticatietype. |

## NetworkCredential::GetCredential(String, int32_t, String) methode

Retourneert referenties voor de opgegeven hostnaam, poort en het authenticatietype.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | [String](../../../system/string/) | De hostnaam. |
| port | **int32_t** | Het poortnummer. |
| authenticationType | [String](../../../system/string/) | Het authenticatietype. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [NetworkCredential](../)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)