---
title: GetValueOf()
second_title: Aspose.Slides для C++ — справочник API
description: Возвращает упакованное значение константы перечисления с указанным именем.
type: docs
weight: 53
url: /ru/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const method

Возвращает упакованное значение константы перечисления с указанным именем.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../string/)\& | Имя константы перечисления |
| ignoreCase | **bool** | Указывает, следует ли игнорировать регистр при интерпретации имени константы перечисления |

### Возвращаемое значение

Упакованное значение константы перечисления, имя которой указано в **str**.

## EnumValues::GetValueOf(long) const method

Возвращает упакованное значение константы перечисления с указанным значением.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| val | long | Значение константы перечисления |

### Возвращаемое значение

Упакованное значение константы перечисления, значение которой указано в **str**.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)