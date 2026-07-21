---
title: GetCultureInfo()
second_title: Справочник API Aspose.Slides для C++
description: Получает культуру по её имени. То же, что CreateSpecificCulture.
type: docs
weight: 586
url: /ru/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) метод

Получает культуру по её имени. То же, что CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Предопределённое имя культуры или имя существующего объекта культуры. |

### Возвращаемое значение

Новый созданный объект культуры.

## CultureInfo::GetCultureInfo(const String\&, const String\&) метод

Получает культуру по её имени.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя культуры. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Имя культуры, используемое для объектов [TextInfo](../../textinfo/) и [CompareInfo](../../compareinfo/). |

### Возвращаемое значение

Объект культуры.

## CultureInfo::GetCultureInfo(int32_t) метод

Получает культуру по идентификатору.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| culture | **int32_t** | Идентификатор культуры. |

### Возвращаемое значение

Новый созданный объект культуры.

## Смотрите также

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Класс [String](../../../system/string/)
* Класс [CultureInfo](../)
* Пространство имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)