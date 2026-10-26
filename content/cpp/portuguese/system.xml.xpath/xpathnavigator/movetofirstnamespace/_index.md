---
title: MoveToFirstNamespace()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, move o XPathNavigator para o primeiro nó de namespace que corresponde ao XPathNamespaceScope especificado.
type: docs
weight: 560
url: /pt/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) método

Quando sobrescrito em uma classe derivada, move o [XPathNavigator](../) para o primeiro nó de namespace que corresponde ao XPathNamespaceScope especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Um valor XPathNamespaceScope que descreve o escopo de namespace. |

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o primeiro nó de namespace; caso contrário, **false**. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## XPathNavigator::MoveToFirstNamespace() método

Move o [XPathNavigator](../) para o primeiro nó de namespace do nó atual.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o primeiro nó de namespace; caso contrário, **false**. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## Veja Também

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)