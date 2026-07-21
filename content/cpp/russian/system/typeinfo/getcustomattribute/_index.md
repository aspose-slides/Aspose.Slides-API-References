---
title: GetCustomAttribute()
second_title: Справочник API Aspose.Slides для C++
description: Ищет пользовательский атрибут указанного типа, примененный к типу, представленному текущим объектом.
type: docs
weight: 573
url: /ru/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const метод


Ищет пользовательский атрибут указанного типа, примененный к типу, представляемому текущим объектом.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Константная ссылка на объект [TypeInfo](../), представляющий тип атрибута для поиска |

### Возвращаемое значение

Указатель на объект, представляющий найденный атрибут, или нулевой указатель, если атрибут, соответствующий критериям поиска, не найден.

## См. также

* Класс [SmartPtr](../../smartptr/)
* Класс [TypeInfo](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)