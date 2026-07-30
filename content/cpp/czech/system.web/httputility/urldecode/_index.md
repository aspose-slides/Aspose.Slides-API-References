---
title: UrlDecode()
second_title: Aspose.Slides pro C++ API Reference
description: Dekóduje fragment URI ze řetězce.
type: docs
weight: 1
url: /cs/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) metoda

Dekóduje fragment URI ze řetězce.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../../../system/string/) | Zakódovaný fragment URI. |

### Návratová hodnota

Dekódovaný fragment URI.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) metoda

Dekóduje fragment URI ze řetězce.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../../../system/string/) | Zakódovaný fragment URI. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Kódování, které se má použít. |

### Návratová hodnota

Dekódovaný fragment URI.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) metoda

Dekóduje fragment URI z pole bajtů.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zakódovaný fragment URI. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kódování, které se má použít. |

### Návratová hodnota

Dekódovaný fragment URI.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) metoda

Dekóduje fragment URI z pole bajtů.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zakódovaný fragment URI. |
| offset | **int32_t** | Posun v daném poli bajtů. |
| count | **int32_t** | Počet bajtů k načtení. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kódování, které se má použít. |

### Návratová hodnota

Dekódovaný fragment URI.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* třída [String](../../../system/string/)
* třída [HttpUtility](../)
* třída [Encoding](../../../system.text/encoding/)
* jmenný prostor [System::Web](../../)
* knihovna [Aspose.Slides](../../../)