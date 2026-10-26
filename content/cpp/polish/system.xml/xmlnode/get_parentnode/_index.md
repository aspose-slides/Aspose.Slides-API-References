---
title: get_ParentNode()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca rodzica tego węzła (dla węzłów, które mogą mieć rodziców).
type: docs
weight: 53
url: /pl/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() metoda

Zwraca rodzica tego węzła (dla węzłów, które mogą mieć rodziców).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### Wartość zwracana

[XmlNode](../) który jest rodzicem bieżącego węzła.

## Uwagi

Jeśli węzeł został właśnie utworzony i nie został jeszcze dodany do drzewa, lub został usunięty z drzewa, rodzic jest **nullptr**. Dla wszystkich innych węzłów zwracana wartość zależy od [XmlNode::get_NodeType](../get_nodetype/) węzła. Poniższa tabela opisuje możliwe wartości zwracane przez metodę **get_NodeType**.

| NodeType | Wartość zwracana ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Zwraca `nullptr`; te węzły nie mają rodziców. |
| CDATA | Zwraca element lub odwołanie do encji zawierające sekcję CDATA. |
| Comment | Zwraca element, odwołanie do encji, typ dokumentu lub dokument zawierający komentarz. |
| DocumentType | Zwraca węzeł dokumentu. |
| Element | Zwraca węzeł rodzica elementu. Jeśli element jest węzłem głównym w drzewie, rodzicem jest węzeł dokumentu. |
| EntityReference | Zwraca element, atrybut lub odwołanie do encji zawierające odwołanie do encji. |
| ProcessingInstruction | Zwraca dokument, element, typ dokumentu lub odwołanie do encji zawierające instrukcję przetwarzania. |
| [Text](../../../system.text/) | Zwraca rodzicielski element, atrybut lub odwołanie do encji zawierające węzeł tekstowy. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)