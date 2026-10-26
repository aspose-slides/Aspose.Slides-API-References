---
title: MoveToNextNamespace()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, move o XPathNavigator para o próximo nó de namespace que corresponde ao XPathNamespaceScope especificado.
type: docs
weight: 573
url: /pt/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) method

Quando sobrescrito em uma classe derivada, move o [XPathNavigator](../) para o próximo nó de namespace que corresponde ao XPathNamespaceScope especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Um valor XPathNamespaceScope que descreve o escopo do namespace. |

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o próximo nó de namespace; caso contrário, **false**. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## XPathNavigator::MoveToNextNamespace() method

Move o [XPathNavigator](../) para o próximo nó de namespace.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o próximo nó de namespace; caso contrário, **false**. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## Veja Também

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)