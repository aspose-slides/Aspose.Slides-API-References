---
title: MoveToFollowing()
second_title: Referencia de API de Aspose.Slides para C++
description: Mueve el XPathNavigator al elemento con el nombre local y el URI del espacio de nombres especificados en orden de documento.
type: docs
weight: 703
url: /es/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) método


Mueve el [XPathNavigator](../) al elemento con el nombre local y el URI del espacio de nombres especificados en orden de documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del elemento. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del elemento. |

### Valor devuelto

**true** si el [XPathNavigator](../) se movió correctamente; de lo contrario, **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) método


Mueve el [XPathNavigator](../) al elemento con el nombre local y el URI del espacio de nombres especificados, al límite especificado, en orden de documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del elemento. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del elemento. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | El objeto [XPathNavigator](../) posicionado en el límite del elemento que el [XPathNavigator](../) actual no superará mientras busca el siguiente elemento. |

### Valor devuelto

**true** si el [XPathNavigator](../) se movió correctamente; de lo contrario, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) método


Mueve el [XPathNavigator](../) al siguiente elemento del XPathNodeType especificado en orden de documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | El XPathNodeType del elemento. El XPathNodeType no puede ser [XPathNodeType::Attribute](../../xpathnodetype/) ni [XPathNodeType::Namespace](../../xpathnodetype/). |

### Valor devuelto

**true** si el [XPathNavigator](../) se movió correctamente; de lo contrario, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) método


Mueve el [XPathNavigator](../) al siguiente elemento del XPathNodeType especificado, al límite especificado, en orden de documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | El XPathNodeType del elemento. El XPathNodeType no puede ser [XPathNodeType::Attribute](../../xpathnodetype/) ni [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | El objeto [XPathNavigator](../) posicionado en el límite del elemento que el [XPathNavigator](../) actual no superará mientras busca el siguiente elemento. |

### Valor devuelto

**true** si el [XPathNavigator](../) se movió correctamente; de lo contrario, **false**.

## Ver también

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)