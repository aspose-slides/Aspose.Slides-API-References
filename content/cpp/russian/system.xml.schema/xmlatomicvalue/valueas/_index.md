---
title: ValueAs()
second_title: Aspose.Slides для C++ справочника API
description: Возвращает значение проверенного XML-элемента или атрибута в указанном типе, используя объект IXmlNamespaceResolver, указанный для разрешения префиксов пространств имён.
type: docs
weight: 144
url: /ru/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) метод

Возвращает значение проверенного XML-элемента или атрибута в указанном типе, используя объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), указанный для разрешения префиксов пространств имён.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Тип, в котором возвращается значение проверенного XML-элемента или атрибута. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. |

### Возвращаемое значение

Значение проверенного XML-элемента или атрибута в запрошенном типе.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Класс [XmlAtomicValue](../)
* Пространство имён [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)