---
title: XPathNodeType
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce i tipi di nodo XPath che possono essere restituiti dalla classe XPathNavigator.
type: docs
weight: 157
url: /it/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Definisce i tipi di nodo [XPath](../) che possono essere restituiti dalla classe [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Root | 0 | Il nodo radice del documento XML o dell'albero di nodi. |
| Element | 1 | Un elemento, come **<element>**. |
| Attribute | 2 | Un attributo, come **id='123'**. |
| Namespace | 3 | Uno spazio dei nomi, come **xmlns=\"namespace\"**. |
| Text | 4 | Il contenuto testuale di un nodo. Equivalente al Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) e ai tipi di nodo CDATA. Contiene almeno un carattere. |
| SignificantWhitespace | 5 | Un nodo con caratteri di spazio bianco e **xml:space** impostato a **preserve**. |
| Whitespace | 6 | Un nodo con solo caratteri di spazio bianco e nessuno spazio bianco significativo. I caratteri di spazio bianco sono **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Un'istruzione di elaborazione, come **<?pi test?>**. Questo non include le dichiarazioni XML, che non sono visibili alla classe [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Un commento, come ****. |
| All | 9 | Qualsiasi dei tipi di nodo XPathNodeType. |

## Vedi anche

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)