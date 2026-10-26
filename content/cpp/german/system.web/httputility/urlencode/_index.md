---
title: UrlEncode()
second_title: Aspose.Slides für C++ API-Referenz
description: Kodiert URI-Fragment.
type: docs
weight: 53
url: /de/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) Methode


Kodiert URI-Fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../../../system/string/) | URI-Fragment zum Kodieren. |

### Rückgabewert

Kodiertes URI-Fragment.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) Methode


Kodiert URI-Fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../../../system/string/) | URI-Fragment zum Kodieren. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Zu verwendende Kodierung. |

### Rückgabewert

Kodiertes URI-Fragment.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) Methode


Kodiert URI-Fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-Fragment zum Kodieren. |

### Rückgabewert

Kodiertes URI-Fragment.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode


Kodiert URI-Fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI-Fragment zum Kodieren. |
| offset | **int32_t** | Versatz im angegebenen Byte-Array. |
| count | **int32_t** | Anzahl der zu lesenden Bytes. |

### Rückgabewert

Kodiertes URI-Fragment.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [HttpUtility](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Namensraum [System::Web](../../)
* Bibliothek [Aspose.Slides](../../../)