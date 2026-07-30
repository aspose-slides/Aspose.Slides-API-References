---
title: UrlEncode()
second_title: Aspose.Slides pro C++ API Reference
description: Zakóduje fragment URI.
type: docs
weight: 53
url: /cs/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) metoda

Zakóduje fragment URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragment URI k zakódování. |

### Návratová hodnota

Zakódovaný fragment URI.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) metoda

Zakóduje fragment URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragment URI k zakódování. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kódování k použití. |

### Návratová hodnota

Zakódovaný fragment URI.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) metoda

Zakóduje fragment URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment URI k zakódování. |

### Návratová hodnota

Zakódovaný fragment URI.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Zakóduje fragment URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment URI k zakódování. |
| offset | **int32_t** | Posun v daném poli bajtů. |
| count | **int32_t** | Počet bajtů ke čtení. |

### Návratová hodnota

Zakódovaný fragment URI.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [HttpUtility](../)
* Třída [Encoding](../../../system.text/encoding/)
* Jmenný prostor [System::Web](../../)
* Knihovna [Aspose.Slides](../../../)