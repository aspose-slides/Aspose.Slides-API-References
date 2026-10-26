---
title: EnumValues
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет метаинформацию о константах перечисления типа E.
type: docs
weight: 794
url: /ru/system/enumvalues/
---
## EnumValues класс

Provides meta information about enumeration constants of enum type **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| E | Тип перечисления |
## Методы

| Method | Description |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Создаёт экземпляр. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Возвращает массив, содержащий все имена перечисления **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Получает массив имён констант в указанном перечислении. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Возвращает базовый тип указанного перечисления. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Возвращает базовый тип указанного перечисления. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Возвращает упакованное значение константы перечисления с указанным именем. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Возвращает упакованное значение константы перечисления с указанным значением. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Возвращает массив, содержащий все значения перечисления **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Возвращает массив, содержащий все значения указанного типа перечисления. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Возвращает объект, представляющий значение константы перечисления указанного типа с указанным именем. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Преобразует указанное 64-битное беззнаковое целое значение в член перечисления. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Преобразует указанный объект с целочисленным значением в член перечисления. |
| virtual  [~EnumValues](./~enumvalues/)() | Деструктор. |

## См. также

* Класс [EnumValuesBase](../enumvaluesbase/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)