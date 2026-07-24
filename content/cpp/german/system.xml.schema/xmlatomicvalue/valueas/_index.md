---
title: ValueAs()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert des validierten XML-Elements oder -Attributs als den angegebenen Typ zurück, wobei das IXmlNamespaceResolver-Objekt zum Auflösen von Namensraumpräfixen verwendet wird.
type: docs
weight: 144
url: /de/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) Methode

Gibt den Wert des validierten XML-Elements oder -Attributs als den angegebenen Typ zurück, wobei das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt zum Auflösen von Namensraumpräfixen verwendet wird.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ, als den der Wert des validierten XML-Elements oder -Attributs zurückgegeben wird. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt, das zum Auflösen von Namensraumpräfixen verwendet wird. |

### Rückgabewert

Der Wert des validierten XML-Elements oder -Attributes als der angeforderte Typ.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XmlAtomicValue](../)
* Namensraum [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)