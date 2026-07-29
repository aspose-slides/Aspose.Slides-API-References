---
title: UrlEncode()
second_title: Aspose.Slides för C++ API-referens
description: Kodar URI-fragment.
type: docs
weight: 53
url: /sv/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) metod

Kodar URI-fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../../../system/string/) | URI-fragment att koda. |

### Returvärde

Kodat URI-fragment.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) metod

Kodar URI-fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../../../system/string/) | URI-fragment att koda. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodning att använda. |

### Returvärde

Kodat URI-fragment.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) metod

Kodar URI-fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-fragment att koda. |

### Returvärde

Kodat URI-fragment.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Kodar URI-fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-fragment att koda. |
| offset | **int32_t** | Förskjutning i den angivna bytearrayen. |
| count | **int32_t** | Antal byte att läsa från. |

### Returvärde

Kodat URI-fragment.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [HttpUtility](../)
* Klass [Encoding](../../../system.text/encoding/)
* Namnrymd [System::Web](../../)
* Bibliotek [Aspose.Slides](../../../)