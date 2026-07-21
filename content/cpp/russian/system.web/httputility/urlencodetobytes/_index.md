---
title: UrlEncodeToBytes()
second_title: Справочник API Aspose.Slides для C++
description: Кодирует фрагмент URI.
type: docs
weight: 66
url: /ru/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) метод

Кодирует фрагмент URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Фрагмент URI для кодирования. |

### Возвращаемое значение

Закодированный фрагмент URI.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) метод

Кодирует фрагмент URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Фрагмент URI для кодирования. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка для использования. |

### Возвращаемое значение

Закодированный фрагмент URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) метод

Кодирует фрагмент URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Фрагмент URI для кодирования. |

### Возвращаемое значение

Закодированный фрагмент URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Кодирует фрагмент URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Фрагмент URI для кодирования. |
| offset | **int32_t** | Смещение в заданном массиве байтов. |
| count | **int32_t** | Количество байтов для чтения. |

### Возвращаемое значение

Закодированный фрагмент URI.

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [HttpUtility](../)
* Класс [Encoding](../../../system.text/encoding/)
* Пространство имён [System::Web](../../)
* Library [Aspose.Slides](../../../)