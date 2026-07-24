---
title: ReadElementContentAs()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Elementinhalt als den angeforderten Typ.
type: docs
weight: 586
url: /de/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) Methode


Liest den Elementinhalt als den angeforderten Typ.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ des zurückzugebenden Wertes. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ein [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)-Objekt, das verwendet wird, um etwaige Namespace-Präfixe im Zusammenhang mit der Typkonvertierung aufzulösen. |

### Return Value

Der Elementinhalt, konvertiert in das angeforderte typisierte Objekt.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) Methode


Überprüft, ob der angegebene lokale Name und die Namespace-URI dem aktuellen Element entsprechen, und liest anschließend den Elementinhalt als den angeforderten Typ.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ des zurückzugebenden Wertes. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Ein [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)-Objekt, das verwendet wird, um etwaige Namespace-Präfixe im Zusammenhang mit der Typkonvertierung aufzulösen. |
| localName | [String](../../../system/string/) | Der lokale Name des Elements. |
| namespaceURI | [String](../../../system/string/) | Die Namespace-URI des Elements. |

### Return Value

Der Elementinhalt, konvertiert in das angeforderte typisierte Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)