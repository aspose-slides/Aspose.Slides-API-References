---
title: Add()
second_title: Aspose.Slides for C++ Справочник API
description: Добавляет новую пользовательскую часть XML.
type: docs
weight: 14
url: /ru/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) метод


Добавляет новую пользовательскую часть XML.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | XML-данные новой части для добавления. |

### Возвращаемое значение

Создана пользовательская часть XML.

## ICustomXmlPartCollection::Add(System::String) метод


Добавляет новую пользовательскую часть XML.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | XML-строка новой части для добавления. |

### Возвращаемое значение

Создана пользовательская часть XML.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) метод


Добавляет новую пользовательскую часть XML.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток ввода с XML-данными новой части для добавления. |

### Возвращаемое значение

Создана пользовательская часть XML.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICustomXmlPart](../../icustomxmlpart/)
* Класс [ICustomXmlPartCollection](../)
* Класс [String](../../../system/string/)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)