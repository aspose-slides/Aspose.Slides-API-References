---
title: CreateHttp()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nową instancję klasy WebRequest przy użyciu określonego identyfikatora URI.
type: docs
weight: 79
url: /pl/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) metoda


Tworzy nową instancję klasy [WebRequest](../) przy użyciu podanego identyfikatora URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | Identyfikator URI używany do utworzenia nowej instancji klasy [WebRequest](../). |

### Wartość zwracana

Nowo utworzona instancja klasy WebRequest.
## Uwagi



Zostanie rzucony wyjątek NotSupportedException, gdy podany identyfikator URI rozpoczyna się jakimkolwiek schematem innym niż [http://](http://) lub [https://](https://). 

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) metoda


Tworzy nową instancję klasy [WebRequest](../) przy użyciu podanego identyfikatora URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Identyfikator URI używany do utworzenia nowej instancji klasy [WebRequest](../). |

### Wartość zwracana

Nowo utworzona instancja klasy WebRequest.
## Uwagi



Zostanie rzucony wyjątek NotSupportedException, gdy podany identyfikator URI rozpoczyna się jakimkolwiek schematem innym niż [http://](http://) lub [https://](https://). 

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [HttpWebRequest](../../httpwebrequest/)
* Klasa [String](../../../system/string/)
* Klasa [WebRequest](../)
* Klasa [Uri](../../../system/uri/)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)