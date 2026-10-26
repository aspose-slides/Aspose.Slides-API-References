---
title: ReadElementContentAs()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el contenido del elemento como el tipo solicitado.
type: docs
weight: 586
url: /es/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método

Lee el contenido del elemento como el tipo solicitado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | El tipo del valor que se devolverá. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que se utiliza para resolver cualquier prefijo de espacio de nombres relacionado con la conversión de tipos. |

### Valor devuelto

El contenido del elemento convertido al objeto del tipo solicitado.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) método

Comprueba que el nombre local y el URI del espacio de nombres especificados coinciden con los del elemento actual, y luego lee el contenido del elemento como el tipo solicitado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | El tipo del valor que se devolverá. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que se utiliza para resolver cualquier prefijo de espacio de nombres relacionado con la conversión de tipos. |
| localName | [String](../../../system/string/) | El nombre local del elemento. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del elemento. |

### Valor devuelto

El contenido del elemento convertido al objeto del tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Clase [XmlReader](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)