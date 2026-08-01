---
title: CreateHttp()
second_title: Aspose.Slides for C++ API-referentie
description: Maakt een nieuw exemplaar van de WebRequest-klasse aan met de opgegeven URI.
type: docs
weight: 79
url: /nl/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) methode

Maakt een nieuw exemplaar van de [WebRequest](../) klasse aan met de opgegeven URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | De URI die wordt gebruikt om een nieuw exemplaar van de [WebRequest](../) klasse aan te maken. |

### Retourwaarde

Een nieuw aangemaakt WebRequest-klasse instance.

## Opmerkingen

NotSupportedException wordt gegooid wanneer de opgegeven URI begint met een ander protocol dan [http://](http://) of [https://](https://).

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) methode

Maakt een nieuw exemplaar van de [WebRequest](../) klasse aan met de opgegeven URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De URI die wordt gebruikt om een nieuw exemplaar van de [WebRequest](../) klasse aan te maken. |

### Retourwaarde

Een nieuw aangemaakt WebRequest-klasse instance.

## Opmerkingen

NotSupportedException wordt gegooid wanneer de opgegeven URI begint met een ander protocol dan [http://](http://) of [https://](https://).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HttpWebRequest](../../httpwebrequest/)
* Klasse [String](../../../system/string/)
* Klasse [WebRequest](../)
* Klasse [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)