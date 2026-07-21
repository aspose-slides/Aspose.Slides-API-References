---
title: CreatePortion()
second_title: Справочник API Aspose.Slides для C++
description: Создает пустую текстовую часть.
type: docs
weight: 1
url: /ru/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() метод


Создает пустую текстовую часть.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### Возвращаемое значение

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) метод


Создает текстовую часть из указанной строки.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Строка. |

### Возвращаемое значение

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) метод


Создает часть, используя указанные данные части.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Часть для использования. |

### Возвращаемое значение

[Portion](../../portion/).

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IPortion](../../iportion/)
* Класс [IPortionFactory](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)