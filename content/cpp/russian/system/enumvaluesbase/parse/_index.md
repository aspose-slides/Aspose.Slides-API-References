---
title: Parse()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает объект, представляющий значение константы перечисления указанного типа перечисления с указанным именем.
type: docs
weight: 27
url: /ru/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) метод

Возвращает объект, представляющий значение константы перечисления указанного типа перечисления с указанным именем.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Объект [TypeInfo](../../typeinfo/), представляющий тип значения перечисления, которое следует вернуть |
| str | const [String](../../string/)\& | Имя константы перечисления |
| ignoreCase | **bool** | Указывает, следует ли игнорировать регистр при интерпретации имени константы перечисления |

### Возвращаемое значение

Объект, представляющий значение константы перечисления, имя которой указано в **str**.

## Смотрите также

* Тип [SharedPtr](../../sharedptr/)
* Класс [Object](../../object/)
* Класс [TypeInfo](../../typeinfo/)
* Класс [String](../../string/)
* Класс [EnumValuesBase](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)