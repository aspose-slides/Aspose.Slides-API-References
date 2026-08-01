---
title: UrlDecode()
second_title: Aspose.Slides voor C++ API-referentie
description: Decodeert een URI-fragment uit een string.
type: docs
weight: 1
url: /nl/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) methode

Decodeert een URI-fragment uit een string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | Geëncodeerd URI-fragment. |

### Retourwaarde

Gedecodeerd URI-fragment.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) methode

Decodeert een URI-fragment uit een string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | Geëncodeerd URI-fragment. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Te gebruiken codering. |

### Retourwaarde

Gedecodeerd URI-fragment.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) methode

Decodeert een URI-fragment van een byte-array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Geëncodeerd URI-fragment. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Te gebruiken codering. |

### Retourwaarde

Gedecodeerd URI-fragment.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) methode

Decodeert een URI-fragment van een byte-array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Geëncodeerd URI-fragment. |
| offset | **int32_t** | Offset in de opgegeven byte-array. |
| count | **int32_t** | Aantal bytes om te lezen. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Te gebruiken codering. |

### Retourwaarde

Gedecodeerd URI-fragment.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [HttpUtility](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)