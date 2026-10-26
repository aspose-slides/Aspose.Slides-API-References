---
title: "System::Xml::Serialization"
second_title: "Справочник API Aspose.Slides для C++"
description: 
type: docs
weight: 1158
url: /ru/system.xml.serialization/
---
## Классы

| Класс | Описание |
| --- | --- |
| [IXmlSerializable](./ixmlserializable/) | Предоставляет пользовательское форматирование для XML-сериализации и десериализации. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [XmlAttributeOverrides](./xmlattributeoverrides/) | Позволяет переопределять атрибуты, когда [XmlSerializer](./xmlserializer/) используется для сериализации или десериализации объекта. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [XmlRootAttribute](./xmlrootattribute/) | Помечает цель атрибута как корневой элемент XML и управляет его XML-сериализацией. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [XmlSerializationReader](./xmlserializationreader/) | Сервисный класс, улучшающий работу [XmlReader](../system.xml/xmlreader/). |
| [XmlSerializationWriter](./xmlserializationwriter/) | Сервисный класс, улучшающий работу [XmlWriter](../system.xml/xmlwriter/). |
| [XmlSerializer](./xmlserializer/) | Выполняет сериализацию и десериализацию объектов в XML-документы и из них. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [XmlSerializerImplementation](./xmlserializerimplementation/) | Внутренний класс для использования с [XmlSerializer](./xmlserializer/). |
| [XmlSerializerNamespaces](./xmlserializernamespaces/) | Содержит пространства имён XML и префиксы, которые [Serialization::XmlSerializer](./xmlserializer/) использует для генерации квалифицированных имён в экземпляре XML-документа. |