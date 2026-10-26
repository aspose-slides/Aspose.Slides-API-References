---
title: UrlEncodeToBytes()
second_title: Aspose.Slides für C++ API-Referenz
description: Kodiert URI-Fragment.
type: docs
weight: 66
url: /de/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) Methode

Kodiert ein URI-Fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | URI-Fragment zum Kodieren. |

### Rückgabewert

Kodierter URI-Fragment.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) Methode

Kodiert ein URI-Fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | URI-Fragment zum Kodieren. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Verwendete Kodierung. |

### Rückgabewert

Kodierter URI-Fragment.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) Methode

Kodiert ein URI-Fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-Fragment zum Kodieren. |

### Rückgabewert

Kodierter URI-Fragment.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Kodiert ein URI-Fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-Fragment zum Kodieren. |
| offset | **int32_t** | Versatz im angegebenen Byte-Array. |
| count | **int32_t** | Anzahl der zu lesenden Bytes. |

### Rückgabewert

Kodierter URI-Fragment.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [HttpUtility](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Namensraum [System::Web](../../)
* Library [Aspose.Slides](../../../)