---
title: CreatePortion()
second_title: Aspose.Slides для C++ API Справочник
description: Создает пустую текстовую часть.
type: docs
weight: 1
url: /ru/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() method


Создает пустую текстовую часть.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```


### Возвращаемое значение

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) method


Создает текстовую часть из указанной строки.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Строка. |

### Возвращаемое значение

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) method


Создает часть, используя указанные данные части.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Часть для использования. |

### Возвращаемое значение

[Portion](../../portion/).

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IPortion](../../iportion/)
* Класс [PortionFactory](../)
* Класс [String](../../../system/string/)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)