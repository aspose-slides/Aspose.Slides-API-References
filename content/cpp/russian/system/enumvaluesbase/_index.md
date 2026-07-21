---
title: EnumValuesBase
second_title: Aspose.Slides для C++ справочника API
description: Базовый класс для класса, представляющего метаинформацию типа перечисления.
type: docs
weight: 807
url: /ru/system/enumvaluesbase/
---
## EnumValuesBase класс

Базовый класс для класса, представляющего метаинформацию типа перечисления.

```cpp
class EnumValuesBase
```

## Методы

| Методы | Описание |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Получает массив имён констант в указанном перечислении. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Возвращает базовый тип указанного перечисления. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Возвращает массив, содержащий все значения указанного типа перечисления. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Возвращает объект, представляющий значение константы перечисления указанного типа перечисления с указанным именем. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Преобразует указанное 64-разрядное беззнаковое целое значение в член перечисления. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Преобразует указанный объект с целочисленным значением в член перечисления. |
## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)