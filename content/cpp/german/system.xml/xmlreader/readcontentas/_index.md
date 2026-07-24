---
title: ReadContentAs()
second_title: Aspose.Slides für C++ API Referenz
description: Liest den Inhalt als ein Objekt des angegebenen Typs.
type: docs
weight: 456
url: /de/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) Methode

Liest den Inhalt als ein Objekt des angegebenen Typs.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ des zurückzugebenden Werts. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ein [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)-Objekt, das verwendet wird, um Namespace-Präfixe im Zusammenhang mit der Typumwandlung aufzulösen. Zum Beispiel kann dies verwendet werden, wenn ein [XmlQualifiedName](../../xmlqualifiedname/)-Objekt in einen **xs:string** konvertiert wird. Dieser Wert kann **nullptr** sein. |

### Rückgabewert

Der zusammengefügte Textinhalt oder Attributwert, der in den angeforderten Typ konvertiert wurde.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)