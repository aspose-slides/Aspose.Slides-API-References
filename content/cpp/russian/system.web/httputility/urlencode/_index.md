---
title: UrlEncode()
second_title: Справочник API Aspose.Slides для C++
description: Кодирует фрагмент URI.
type: docs
weight: 53
url: /ru/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) метод

Кодирует фрагмент URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../../../system/string/) | Фрагмент URI для кодирования. |

### Возвращаемое значение

Закодированный фрагмент URI.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) метод

Кодирует фрагмент URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../../../system/string/) | Фрагмент URI для кодирования. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка для использования. |

### Возвращаемое значение

Закодированный фрагмент URI.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) метод

Кодирует фрагмент URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Фрагмент URI для кодирования. |

### Возвращаемое значение

Закодированный фрагмент URI.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Кодирует фрагмент URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Фрагмент URI для кодирования. |
| offset | **int32_t** | Смещение в указанном массиве байтов. |
| count | **int32_t** | Количество байтов для чтения. |

### Возвращаемое значение

Закодированный фрагмент URI.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [HttpUtility](../)
* Класс [Encoding](../../../system.text/encoding/)
* Пространство имён [System::Web](../../)
* Библиотека [Aspose.Slides](../../../)