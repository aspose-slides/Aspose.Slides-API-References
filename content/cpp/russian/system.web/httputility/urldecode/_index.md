---
title: UrlDecode()
second_title: Aspose.Slides для C++: справочник API
description: Декодирует фрагмент URI из строки.
type: docs
weight: 1
url: /ru/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) метод


Декодирует фрагмент URI из строки.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../../../system/string/) | Закодированный фрагмент URI. |

### Возвращаемое значение

Декодированный фрагмент URI.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) метод


Декодирует фрагмент URI из строки.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../../../system/string/) | Закодированный фрагмент URI. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Кодировка для использования. |

### Возвращаемое значение

Декодированный фрагмент URI.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) метод


Декодирует фрагмент URI из массива байтов.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Закодированный фрагмент URI. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка для использования. |

### Возвращаемое значение

Декодированный фрагмент URI.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) метод


Декодирует фрагмент URI из массива байтов.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Закодированный фрагмент URI. |
| offset | **int32_t** | Смещение в указанном массиве байтов. |
| count | **int32_t** | Количество байтов для чтения. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка для использования. |

### Возвращаемое значение

Декодированный фрагмент URI.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [HttpUtility](../)
* Класс [Encoding](../../../system.text/encoding/)
* Пространство имён [System::Web](../../)
* Библиотека [Aspose.Slides](../../../)