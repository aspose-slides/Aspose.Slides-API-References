---
title: get_ParentNode()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací rodiče tohoto uzlu (pro uzly, které mohou mít rodiče).
type: docs
weight: 53
url: /cs/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() metoda

Vrací rodiče tohoto uzlu (pro uzly, které mohou mít rodiče).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### Návratová hodnota

[XmlNode](../), který je rodičem aktuálního uzlu.

## Poznámky



Pokud byl uzel právě vytvořen a ještě není přidán do stromu, nebo byl ze stromu odebrán, rodič je **nullptr**. Pro všechny ostatní uzly závisí vrácená hodnota na [XmlNode::get_NodeType](../get_nodetype/) uzlu. Následující tabulka popisuje možné návratové hodnoty pro metodu **get_NodeType**. 

| NodeType | Návratová hodnota ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Vrací `nullptr`; tyto uzly nemají rodiče. |
| CDATA | Vrací element nebo odkaz na entitu, který obsahuje sekci CDATA. |
| Comment | Vrací element, odkaz na entitu, typ dokumentu nebo dokument, který obsahuje komentář. |
| DocumentType | Vrací uzel dokumentu. |
| Element | Vrací rodičovský uzel elementu. Pokud je element kořenovým uzlem ve stromě, rodič je uzel dokumentu. |
| EntityReference | Vrací element, atribut nebo odkaz na entitu, který obsahuje odkaz na entitu. |
| ProcessingInstruction | Vrací dokument, element, typ dokumentu nebo odkaz na entitu, který obsahuje instrukci zpracování. |
| [Text](../../../system.text/)| Vrací rodičovský element, atribut nebo odkaz na entitu, který obsahuje textový uzel. |


## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../)
* Namespace [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)