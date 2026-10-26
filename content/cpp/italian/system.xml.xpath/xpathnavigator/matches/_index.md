---
title: Matches()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se il nodo corrente corrisponde all'XPathExpression specificata.
type: docs
weight: 820
url: /it/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) metodo

Determina se il nodo corrente corrisponde al [XPathExpression](../../xpathexpression/) specificato.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un oggetto [XPathExpression](../../xpathexpression/) contenente l'espressione [XPath](../../) compilata. |

### Valore di ritorno

**true** se il nodo corrente corrisponde al [XPathExpression](../../xpathexpression/); altrimenti, **false**.

## XPathNavigator::Matches(String) metodo

Determina se il nodo corrente corrisponde all'espressione [XPath](../../) specificata.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | L'espressione [XPath](../../). |

### Valore di ritorno

**true** se il nodo corrente corrisponde all'espressione [XPath](../../) specificata; altrimenti, **false**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathExpression](../../xpathexpression/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)