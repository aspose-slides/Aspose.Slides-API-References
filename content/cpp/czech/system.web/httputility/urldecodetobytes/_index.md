---
title: UrlDecodeToBytes()
second_title: Aspose.Slides pro C++ API Reference
description: Dekóduje fragment URI z bytového pole.
type: docs
weight: 14
url: /cs/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metoda


Dekóduje fragment URI z bytového pole.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zakódovaný fragment URI. |

### Návratová hodnota

Dekódovaný fragment URI.

## HttpUtility::UrlDecodeToBytes(const String\&) metoda


Dekóduje fragment URI z řetězce bajtů.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Zakódovaný fragment URI. |

### Návratová hodnota

Dekódovaný fragment URI.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metoda


Dekóduje fragment URI ze řetězce.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Zakódovaný fragment URI. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kódování k použití. |

### Návratová hodnota

Dekódovaný fragment URI.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Dekóduje fragment URI z bytového pole.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zakódovaný fragment URI. |
| offset | **int32_t** | Posun v daném bytovém poli. |
| count | **int32_t** | Počet bajtů, které se mají načíst. |

### Návratová hodnota

Dekódovaný fragment URI.

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [HttpUtility](../)
* Třída [String](../../../system/string/)
* Třída [Encoding](../../../system.text/encoding/)
* Jmenný prostor [System::Web](../../)
* Knihovna [Aspose.Slides](../../../)