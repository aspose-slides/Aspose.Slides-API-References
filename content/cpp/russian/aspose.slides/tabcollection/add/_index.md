---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет вкладку в коллекцию.
type: docs
weight: 53
url: /ru/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) метод

Добавляет [Tab](../../tab/) в коллекцию.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```


### Возвращаемое значение

Добавленная вкладка.

## TabCollection::Add(System::SharedPtr\<ITab\>) метод


Добавляет [Tab](../../tab/) в коллекцию.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Объект [Tab](../../tab/), который будет добавлен в конец коллекции. |

### Возвращаемое значение

Индекс, по которому была добавлена вкладка.

## См. также

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ITab](../../itab/)
* Класс [TabCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)