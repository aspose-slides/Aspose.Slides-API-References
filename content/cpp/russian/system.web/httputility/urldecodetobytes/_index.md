---
title: UrlDecodeToBytes()
second_title: Справочник API Aspose.Slides для C++
description: Декодирует фрагмент URI из массива байтов.
type: docs
weight: 14
url: /ru/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method

Декодирует фрагмент URI из массива байтов.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Закодированный фрагмент URI. |

### Return Value

Декодированный фрагмент URI.

## HttpUtility::UrlDecodeToBytes(const String\&) method

Декодирует фрагмент URI из строки.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Закодированный фрагмент URI. |

### Return Value

Декодированный фрагмент URI.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method

Декодирует фрагмент URI из строки.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Закодированный фрагмент URI. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка для использования. |

### Return Value

Декодированный фрагмент URI.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Декодирует фрагмент URI из массива байтов.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Закодированный фрагмент URI. |
| offset | **int32_t** | Смещение в данном массиве байтов. |
| count | **int32_t** | Количество байтов для чтения. |

### Return Value

Декодированный фрагмент URI.

## See Also

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [HttpUtility](../)
* Класс [String](../../../system/string/)
* Класс [Encoding](../../../system.text/encoding/)
* Пространство имён [System::Web](../../)
* Библиотека [Aspose.Slides](../../../)