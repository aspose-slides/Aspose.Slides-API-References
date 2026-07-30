---
title: UrlEncodeToBytes()
second_title: Aspose.Slides pro C++ reference API
description: Zakóduje fragment URI.
type: docs
weight: 66
url: /cs/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) metoda


Zakóduje fragment URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragment URI k zakódování. |

### Návratová hodnota

Zakódovaný fragment URI.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metoda


Zakóduje fragment URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragment URI k zakódování. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kódování k použití. |

### Návratová hodnota

Zakódovaný fragment URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metoda


Zakóduje fragment URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment URI k zakódování. |

### Návratová hodnota

Zakódovaný fragment URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Zakóduje fragment URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment URI k zakódování. |
| offset | **int32_t** | Posun v daném poli bajtů. |
| count | **int32_t** | Počet bajtů k přečtení. |

### Návratová hodnota

Zakódovaný fragment URI.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [HttpUtility](../)
* Třída [Encoding](../../../system.text/encoding/)
* Jmenný prostor [System::Web](../../)
* Knihovna [Aspose.Slides](../../../)