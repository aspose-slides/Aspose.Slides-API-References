---
title: WriteNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, copia todo del lector al escritor y desplaza el lector al inicio del siguiente hermano.
type: docs
weight: 430
url: /es/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) método

Cuando se sobrescribe en una clase derivada, copia todo del lector al escritor y desplaza el lector al inicio del siguiente hermano.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | El [XmlReader](../../xmlreader/) del que leer. |
| defattr | **bool** | **true** para copiar los atributos predeterminados del [XmlReader](../../xmlreader/); de lo contrario, **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) método

Copia todo del objeto XPathNavigator al escritor. La posición del XPathNavigator permanece sin cambios.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | El XPathNavigator del que copiar. |
| defattr | **bool** | **true** para copiar los atributos predeterminados; de lo contrario, **false**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlReader](../../xmlreader/)
* Clase [XmlWriter](../)
* Clase [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)