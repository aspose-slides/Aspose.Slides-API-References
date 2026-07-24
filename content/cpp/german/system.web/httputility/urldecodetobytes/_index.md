---
title: UrlDecodeToBytes()
second_title: Aspose.Slides für C++ API-Referenz
description: Dekodiert das URI-Fragment aus einem Byte-Array.
type: docs
weight: 14
url: /de/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) Methode

Dekodiert das URI-Fragment aus einem Byte-Array.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodiertes URI-Fragment. |

### Rückgabewert

Dekodiertes URI-Fragment.

## HttpUtility::UrlDecodeToBytes(const String\&) Methode

Dekodiert das URI-Fragment aus einer Byte-Zeichenkette.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kodiertes URI-Fragment. |

### Rückgabewert

Dekodiertes URI-Fragment.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) Methode

Dekodiert das URI-Fragment aus einer Zeichenkette.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kodiertes URI-Fragment. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Zu verwendende Kodierung. |

### Rückgabewert

Dekodiertes URI-Fragment.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Dekodiert das URI-Fragment aus einem Byte-Array.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodiertes URI-Fragment. |
| offset | **int32_t** | Versatz im angegebenen Byte-Array. |
| count | **int32_t** | Anzahl der zu lesenden Bytes. |

### Rückgabewert

Dekodiertes URI-Fragment.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HttpUtility](../)
* Klasse [String](../../../system/string/)
* Klasse [Encoding](../../../system.text/encoding/)
* Namensraum [System::Web](../../)
* Bibliothek [Aspose.Slides](../../../)