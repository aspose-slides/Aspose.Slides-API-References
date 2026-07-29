---
title: UrlDecodeToBytes()
second_title: Aspose.Slides för C++ API-referens
description: Avkodar URI-fragment från bytearray.
type: docs
weight: 14
url: /sv/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metod

Avkodar URI-fragment från bytearray.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodat URI-fragment. |

### Returvärde

Avkodad URI-fragment.

## HttpUtility::UrlDecodeToBytes(const String\&) metod

Avkodar URI-fragment från byte-sträng.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kodat URI-fragment. |

### Returvärde

Avkodad URI-fragment.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metod

Avkodar URI-fragment från sträng.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kodat URI-fragment. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodning att använda. |

### Returvärde

Avkodad URI-fragment.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Avkodar URI-fragment från bytearray.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodat URI-fragment. |
| offset | **int32_t** | Offset i den angivna bytearrayen. |
| count | **int32_t** | Antal byte att läsa från. |

### Returvärde

Avkodad URI-fragment.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [HttpUtility](../)
* Klass [String](../../../system/string/)
* Klass [Encoding](../../../system.text/encoding/)
* Namnrymd [System::Web](../../)
* Library [Aspose.Slides](../../../)