---
title: MoveToFollowing()
second_title: Referência da API Aspose.Slides para C++ 
description: Move o XPathNavigator para o elemento com o nome local e o URI do namespace especificados na ordem do documento.
type: docs
weight: 703
url: /pt/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) método

Move o [XPathNavigator](../) para o elemento com o nome local e o URI do namespace especificados na ordem do documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |

### Valor de Retorno

**true** se o [XPathNavigator](../) mover-se com sucesso; caso contrário, **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) método

Move o [XPathNavigator](../) para o elemento com o nome local e o URI do namespace especificados, até o limite especificado, na ordem do documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the element. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the element. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | The [XPathNavigator](../) object positioned on the element boundary which the current [XPathNavigator](../) will not move past while searching for the following element. |

### Valor de Retorno

**true** se o [XPathNavigator](../) mover-se com sucesso; caso contrário, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) método

Move o [XPathNavigator](../) para o próximo elemento do XPathNodeType especificado na ordem do documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the element. The XPathNodeType cannot be [XPathNodeType::Attribute](../../xpathnodetype/) or [XPathNodeType::Namespace](../../xpathnodetype/). |

### Valor de Retorno

**true** se o [XPathNavigator](../) mover-se com sucesso; caso contrário, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) método

Move o [XPathNavigator](../) para o próximo elemento do XPathNodeType especificado, até o limite especificado, na ordem do documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the element. The XPathNodeType cannot be [XPathNodeType::Attribute](../../xpathnodetype/) or [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | The [XPathNavigator](../) object positioned on the element boundary which the current [XPathNavigator](../) will not move past while searching for the following element. |

### Valor de Retorno

**true** se o [XPathNavigator](../) mover-se com sucesso; caso contrário, **false**.

## Veja Também

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)