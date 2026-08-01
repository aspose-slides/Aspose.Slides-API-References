---
title: UrlDecodeToBytes()
second_title: Aspose.Slides voor C++ API-referentie
description: Decodeert URI-fragment uit een byte-array.
type: docs
weight: 14
url: /nl/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) methode


Decodeert URI-fragment uit een byte-array.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Gecodeerd URI-fragment. |

### Retourwaarde

Gedecodeerd URI-fragment.

## HttpUtility::UrlDecodeToBytes(const String\&) methode


Decodeert URI-fragment uit een byte-string.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Gecodeerd URI-fragment. |

### Retourwaarde

Gedecodeerd URI-fragment.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) methode


Decodeert URI-fragment uit een tekenreeks.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Gecodeerd URI-fragment. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Te gebruiken codering. |

### Retourwaarde

Gedecodeerd URI-fragment.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Decodeert URI-fragment uit een byte-array.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Gecodeerd URI-fragment. |
| offset | **int32_t** | Offset in de gegeven byte-array. |
| count | **int32_t** | Aantal bytes om van te lezen. |

### Retourwaarde

Gedecodeerd URI-fragment.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HttpUtility](../)
* Klasse [String](../../../system/string/)
* Klasse [Encoding](../../../system.text/encoding/)
* Naamruimte [System::Web](../../)
* Library [Aspose.Slides](../../../)