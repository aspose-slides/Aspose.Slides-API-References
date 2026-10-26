---
title: CreateHttp()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av WebRequest-klassen med den angivna URI:n.
type: docs
weight: 79
url: /sv/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) metod

Skapar en ny instans av [WebRequest](../)-klassen med den angivna URI:n.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | URI:n som används för att skapa en ny instans av [WebRequest](../)-klassen. |

### Return Value

En nyinstans av WebRequest-klassen.

## Remarks

NotSupportedException kommer att kastas när den angivna URI:n börjar med ett schema annat än [http://](http://) eller [https://](https://).

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) metod

Skapar en ny instans av [WebRequest](../)-klassen med den angivna URI:n.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI:n som används för att skapa en ny instans av [WebRequest](../)-klassen. |

### Return Value

En nyinstans av WebRequest-klassen.

## Remarks

NotSupportedException kommer att kastas när den angivna URI:n börjar med ett schema annat än [http://](http://) eller [https://](https://).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [HttpWebRequest](../../httpwebrequest/)
* Klass [String](../../../system/string/)
* Klass [WebRequest](../)
* Klass [Uri](../../../system/uri/)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)