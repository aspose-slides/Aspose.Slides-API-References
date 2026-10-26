---
title: UrlDecode()
second_title: Aspose.Slides für C++ API-Referenz
description: Dekodiert URI-Fragment aus einem String.
type: docs
weight: 1
url: /de/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) Methode

Dekodiert URI-Fragment aus einem String.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kodiertes URI-Fragment. |

### Rückgabewert

Dekodiertes URI-Fragment.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) Methode

Dekodiert URI-Fragment aus einem String.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kodiertes URI-Fragment. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Zu verwendende Kodierung. |

### Rückgabewert

Dekodiertes URI-Fragment.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) Methode

Dekodiert URI-Fragment aus einem Byte-Array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodiertes URI-Fragment. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Zu verwendende Kodierung. |

### Rückgabewert

Dekodiertes URI-Fragment.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) Methode

Dekodiert URI-Fragment aus einem Byte-Array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodiertes URI-Fragment. |
| offset | **int32_t** | Versatz im angegebenen Byte-Array. |
| count | **int32_t** | Anzahl der Bytes, die gelesen werden sollen. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Zu verwendende Kodierung. |

### Rückgabewert

Dekodiertes URI-Fragment.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [HttpUtility](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Namensraum [System::Web](../../)
* Library [Aspose.Slides](../../../)