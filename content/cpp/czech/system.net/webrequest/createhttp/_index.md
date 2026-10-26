---
title: CreateHttp()
second_title: Referenční příručka Aspose.Slides pro C++
description: Vytvoří novou instanci třídy WebRequest pomocí zadaného URI.
type: docs
weight: 79
url: /cs/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) metoda


Vytvoří novou instanci třídy [WebRequest](../) pomocí zadaného URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | URI, které se používá k vytvoření nové instance třídy [WebRequest](../). |

### Návratová hodnota

Nově vytvořená instance třídy WebRequest.
## Poznámky



NotSupportedException bude vyvolána, pokud zadané URI začíná jakýmkoli schématem kromě [http://](http://) nebo [https://](https://). 

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) metoda


Vytvoří novou instanci třídy [WebRequest](../) pomocí zadaného URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, které se používá k vytvoření nové instance třídy [WebRequest](../). |

### Návratová hodnota

Nově vytvořená instance třídy WebRequest.
## Poznámky



NotSupportedException bude vyvolána, pokud zadané URI začíná jakýmkoli schématem kromě [http://](http://) nebo [https://](https://). 

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)