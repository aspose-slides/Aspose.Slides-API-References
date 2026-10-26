---
title: MoveToNext()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, move o XPathNavigator para o próximo nó irmão do nó atual.
type: docs
weight: 586
url: /pt/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() método

Quando sobrescrito em uma classe derivada, move o [XPathNavigator](../) para o próximo nó irmão do nó atual.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o próximo nó irmão; caso contrário **false** se não houver mais irmãos ou se o [XPathNavigator](../) estiver atualmente posicionado em um nó de atributo. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## XPathNavigator::MoveToNext(String, String) método

Move o [XPathNavigator](../) para o próximo nó irmão com o nome local e o URI de namespace especificados.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do próximo nó irmão para o qual mover. |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do próximo nó irmão para o qual mover. |

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o próximo nó irmão; **false** se não houver mais irmãos, ou se o [XPathNavigator](../) estiver atualmente posicionado em um nó de atributo. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## XPathNavigator::MoveToNext(XPathNodeType) método

Move o [XPathNavigator](../) para o próximo nó irmão do nó atual que corresponde ao XPathNodeType especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | O XPathNodeType do nó irmão para o qual mover. |

### Valor de Retorno

**true** se o [XPathNavigator](../) for bem-sucedido ao mover para o próximo nó irmão; caso contrário, **false** se não houver mais irmãos ou se o [XPathNavigator](../) estiver atualmente posicionado em um nó de atributo. Se **false**, a posição do [XPathNavigator](../) permanece inalterada.

## Veja Também

* Enum [XPathNodeType](../../xpathnodetype/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)