---
title: UrlEncodeToBytes()
second_title: Aspose.Slides voor C++ API-referentie
description: Encodeert URI-fragment.
type: docs
weight: 66
url: /nl/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) methode


Encodeert URI-fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | URI-fragment om te encoderen. |

### Retourwaarde

Geëcodeerd URI-fragment.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) methode


Encodeert URI-fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | URI-fragment om te encoderen. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Te gebruiken codering. |

### Retourwaarde

Geëcodeerd URI-fragment.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) methode


Encodeert URI-fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-fragment om te encoderen. |

### Retourwaarde

Geëcodeerd URI-fragment.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Encodeert URI-fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-fragment om te encoderen. |
| offset | **int32_t** | Offset in de opgegeven byte-array. |
| count | **int32_t** | Aantal bytes om van te lezen. |

### Retourwaarde

Geëcodeerd URI-fragment.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [HttpUtility](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Naamruimte [System::Web](../../)
* Library [Aspose.Slides](../../../)