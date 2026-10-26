---
title: MoveToFollowing()
second_title: Riferimento API di Aspose.Slides per C++
description: Sposta lo XPathNavigator sull'elemento con il nome locale e l'URI dello spazio dei nomi specificati nell'ordine del documento.
type: docs
weight: 703
url: /it/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) metodo

Sposta il [XPathNavigator](../) sull'elemento con il nome locale e l'URI dello spazio dei nomi specificati nell'ordine del documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'elemento. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'elemento. |

### Valore di ritorno

**true** se il [XPathNavigator](../) è stato spostato con successo; altrimenti, **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) metodo

Sposta il [XPathNavigator](../) sull'elemento con il nome locale e l'URI dello spazio dei nomi specificati, al limite specificato, nell'ordine del documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'elemento. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'elemento. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | L'oggetto [XPathNavigator](../) posizionato sul limite dell'elemento che il corrente [XPathNavigator](../) non supererà durante la ricerca dell'elemento successivo. |

### Valore di ritorno

**true** se il [XPathNavigator](../) è stato spostato con successo; altrimenti, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) metodo

Sposta il [XPathNavigator](../) sull'elemento successivo del XPathNodeType specificato, nell'ordine del documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Il XPathNodeType dell'elemento. Il XPathNodeType non può essere [XPathNodeType::Attribute](../../xpathnodetype/) o [XPathNodeType::Namespace](../../xpathnodetype/). |

### Valore di ritorno

**true** se il [XPathNavigator](../) è stato spostato con successo; altrimenti, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) metodo

Sposta il [XPathNavigator](../) sull'elemento successivo del XPathNodeType specificato, al limite specificato, nell'ordine del documento.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Il XPathNodeType dell'elemento. Il XPathNodeType non può essere [XPathNodeType::Attribute](../../xpathnodetype/) o [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | L'oggetto [XPathNavigator](../) posizionato sul limite dell'elemento che il corrente [XPathNavigator](../) non supererà durante la ricerca dell'elemento successivo. |

### Valore di ritorno

**true** se il [XPathNavigator](../) è stato spostato con successo; altrimenti, **false**.

## Vedi anche

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)