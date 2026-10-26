---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет новую пользовательскую XML-часть.
type: docs
weight: 53
url: /ru/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) метод

Добавляет новую пользовательскую XML-часть.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | XML-строка новой части, которая будет добавлена. |

### Возвращаемое значение

Создана пользовательская XML-часть.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) метод

Добавляет новую пользовательскую XML-часть.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | XML-данные новой части, которые необходимо добавить. |

### Возвращаемое значение

Создана пользовательская XML-часть.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) метод

Добавляет новую пользовательскую XML-часть.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток ввода с XML-данными новой части, который необходимо добавить. |

### Возвращаемое значение

Создана пользовательская XML-часть.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICustomXmlPart](../../icustomxmlpart/)
* Класс [String](../../../system/string/)
* Класс [CustomXmlPartCollection](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)