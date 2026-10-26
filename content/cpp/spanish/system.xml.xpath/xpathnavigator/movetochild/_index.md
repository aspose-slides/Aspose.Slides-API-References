---
title: MoveToChild()
second_title: Referencia de API de Aspose.Slides para C++
description: Mueve el XPathNavigator al nodo hijo con el nombre local y el URI del espacio de nombres especificados.
type: docs
weight: 690
url: /es/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) método

Mueve el [XPathNavigator](../) al nodo hijo con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del nodo hijo al que moverse. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del nodo hijo al que moverse. |

### Valor de retorno

**true** si el [XPathNavigator](../) se mueve correctamente al nodo hijo; de lo contrario, **false**. Si **false**, la posición del [XPathNavigator](../) no cambia.

## XPathNavigator::MoveToChild(XPathNodeType) método

Mueve el [XPathNavigator](../) al nodo hijo del XPathNodeType especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | El XPathNodeType del nodo hijo al que moverse. |

### Valor de retorno

**true** si el [XPathNavigator](../) se mueve correctamente al nodo hijo; de lo contrario, **false**. Si **false**, la posición del [XPathNavigator](../) no cambia.

## Ver también

* Enumeración [XPathNodeType](../../xpathnodetype/)
* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)