---
title: UrlEncode()
second_title: Aspose.Slides for C++ API Referentie
description: Encodeert URI-fragment.
type: docs
weight: 53
url: /nl/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) methode


Encodeert URI-fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [String](../../../system/string/) | URI-fragment om te coderen. |

### Retourwaarde

Geëcodeerd URI-fragment.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) methode


Encodeert URI-fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [String](../../../system/string/) | URI-fragment om te coderen. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Te gebruiken codering. |

### Retourwaarde

Geëcodeerd URI-fragment.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) methode


Encodeert URI-fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-fragment om te coderen. |

### Retourwaarde

Geëcodeerd URI-fragment.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode


Encodeert URI-fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-fragment om te coderen. |
| offset | **int32_t** | Offset in de gegeven byte-array. |
| count | **int32_t** | Aantal bytes om van te lezen. |

### Retourwaarde

Geëcodeerd URI-fragment.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [HttpUtility](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Naamruimte [System::Web](../../)
* Library [Aspose.Slides](../../../)