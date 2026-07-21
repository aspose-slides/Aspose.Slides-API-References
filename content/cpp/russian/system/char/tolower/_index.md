---
title: ToLower()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанный символ в нижний регистр.
type: docs
weight: 235
url: /ru/system/char/tolower/
---
## Char::ToLower(char_t) метод

Преобразует указанный символ в нижний регистр.

```cpp
static char_t System::Char::ToLower(char_t c)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Символ для преобразования |

### Возвращаемое значение

Указанный символ в нижнем регистре, если указанный символ является прописной буквой, иначе — указанный символ

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) метод

Преобразует указанный символ в нижний регистр.

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Символ для преобразования |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Объект, предоставляющий правила преобразования регистра, зависящие от культуры. |

### Возвращаемое значение

Указанный символ в нижнем регистре, если указанный символ является прописной буквой, иначе — указанный символ

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [Char](../)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)