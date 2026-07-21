---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет Tab в коллекцию.
type: docs
weight: 14
url: /ru/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) метод


Добавляет [Tab](../../tab/) в коллекцию.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) позиция. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) выравнивание. |

### Возвращаемое значение

Добавленная табуляция.

## ITabCollection::Add(System::SharedPtr\<ITab\>) метод


Добавляет [Tab](../../tab/) в коллекцию.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Объект [Tab](../../tab/), который будет добавлен в конец коллекции. |

### Возвращаемое значение

Индекс, по которому была добавлена табуляция.

## См. также

* Перечисление [TabAlignment](../../tabalignment/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ITab](../../itab/)
* Класс [ITabCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)