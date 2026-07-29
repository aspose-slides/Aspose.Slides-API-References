---
title: UrlDecode()
second_title: Aspose.Slides för C++ API-referens
description: Avkodar URI-fragment från sträng.
type: docs
weight: 1
url: /sv/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) metod


Avkodar URI-fragment från sträng.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kodad URI-fragment. |

### Returvärde

Avkodat URI-fragment.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) metod


Avkodar URI-fragment från sträng.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kodad URI-fragment. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Kodning att använda. |

### Returvärde

Avkodat URI-fragment.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) metod


Avkodar URI-fragment från byte-array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodad URI-fragment. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodning att använda. |

### Returvärde

Avkodat URI-fragment.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) metod


Avkodar URI-fragment från byte-array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodad URI-fragment. |
| offset | **int32_t** | Offset i den angivna byte-arrayen. |
| count | **int32_t** | Antal byte att läsa från. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodning att använda. |

### Returvärde

Avkodat URI-fragment.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)