---
title: CreateHttp()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz der WebRequest-Klasse mit der angegebenen URI.
type: docs
weight: 79
url: /de/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) Methode

Erstellt eine neue Instanz der [WebRequest](../) Klasse mit der angegebenen URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | Die URI, die verwendet wird, um eine neue Instanz der [WebRequest](../) Klasse zu erstellen. |

### Rückgabewert

Eine neu erstellte WebRequest-class Instanz.
## Hinweise

Eine NotSupportedException wird ausgelöst, wenn die angegebene URI mit einem anderen Schema als [http://](http://) oder [https://](https://) beginnt.

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) Methode

Erstellt eine neue Instanz der [WebRequest](../) Klasse mit der angegebenen URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die URI, die verwendet wird, um eine neue Instanz der [WebRequest](../) Klasse zu erstellen. |

### Rückgabewert

Eine neu erstellte WebRequest-class Instanz.
## Hinweise

Eine NotSupportedException wird ausgelöst, wenn die angegebene URI mit einem anderen Schema als [http://](http://) oder [https://](https://) beginnt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)