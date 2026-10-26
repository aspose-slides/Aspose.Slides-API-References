---
title: Is()
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 27
url: /ru/system.threading/details_threadstateexception/is/
---
## Подробности_ThreadStateException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Threading::Details_ThreadStateException::Is(const System::TypeInfo &target) const override
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) структура, описывающая тип, против которого проверяется текущий объект. |

### Возвращаемое значение

True, если объект имеет помеченный тип или его подкласс; false в противном случае.
## Замечания

Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'.


## См. также

* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [Details_ThreadStateException](../)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)