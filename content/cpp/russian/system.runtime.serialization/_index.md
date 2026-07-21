---
title: "System::Runtime::Serialization"
second_title: "Справочник API Aspose.Slides для C++"
description: 
type: docs
weight: 794
url: /ru/system.runtime.serialization/
---
## Классы

| Класс | Описание |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Представляет базовую реализацию интерфейса [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | Обеспечивает связь между экземпляром [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) и классом, предоставляемым форматировщиком, наиболее подходящим для разбора данных внутри [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Интерфейс объекта, который может быть сериализован. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Нельзя создавать экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель при передаче в функции в качестве аргумента. |
| [SerializationInfo](./serializationinfo/) | Содержит набор именованных полей, представляющих сериализованный объект. Не реализовано. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Нельзя создавать экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель при передаче в функции в качестве аргумента. |
| [StreamingContext](./streamingcontext/) | Фиктивный класс, позволяющий скомпилировать переведённые классы, использующие StreamingContext. Не управляйте экземплярами этого класса через [SmartPtr](../system/smartptr/), они должны выделяться только в стеке. |
## Типы

| Тип | Описание |
| --- | --- |
| [SerializationException](./serializationexception/) |  |