---
title: ReadContentAs()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el contenido como un objeto del tipo especificado.
type: docs
weight: 456
url: /es/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método

Lee el contenido como un objeto del tipo especificado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | El tipo del valor que se devolverá. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que se utiliza para resolver cualquier prefijo de espacio de nombres relacionado con la conversión de tipo. Por ejemplo, esto puede usarse al convertir un objeto [XmlQualifiedName](../../xmlqualifiedname/) a un **xs:string**. Este valor puede ser **nullptr**. |

### Valor devuelto

El contenido de texto concatenado o el valor del atributo convertido al tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)