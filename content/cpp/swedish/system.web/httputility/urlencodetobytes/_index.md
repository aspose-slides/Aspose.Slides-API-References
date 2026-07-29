---
title: UrlEncodeToBytes()
second_title: Aspose.Slides för C++ API-referens
description: Kodar URI-fragment.
type: docs
weight: 66
url: /sv/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) metod


Kodar URI-fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | URI-fragment att koda. |

### Returvärde

Kodad URI-fragment.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metod


Kodar URI-fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | URI-fragment att koda. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodning att använda. |

### Returvärde

Kodad URI-fragment.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metod


Kodar URI-fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-fragment att koda. |

### Returvärde

Kodad URI-fragment.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Kodar URI-fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-fragment att koda. |
| offset | **int32_t** | Offset i den angivna byte-arrayen. |
| count | **int32_t** | Antal byte att läsa från. |

### Returvärde

Kodad URI-fragment.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [HttpUtility](../)
* Klass [Encoding](../../../system.text/encoding/)
* Namnrymd [System::Web](../../)
* Bibliotek [Aspose.Slides](../../../)