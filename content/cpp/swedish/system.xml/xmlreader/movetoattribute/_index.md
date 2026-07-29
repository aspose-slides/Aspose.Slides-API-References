---
title: MoveToAttribute()
second_title: Aspose.Slides för C++ API-referens
description: "När den åsidosätts i en avledd klass, flyttas den till attributet med det angivna XmlReader::get_Name-värdet."
type: docs
weight: 625
url: /sv/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) metod

När den åsidosätts i en avledd klass, flyttas den till attributet med det angivna [XmlReader::get_Name](../get_name/)-värdet.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på attributet. |

### Returvärde

**true** om attributet hittas; annars **false**. Om **false**, ändras inte läsarens position.

## XmlReader::MoveToAttribute(String, String) metod

När den åsidosätts i en avledd klass, flyttas den till attributet med de angivna [XmlReader::get_LocalName](../get_localname/)- och [XmlReader::get_NamespaceURI](../get_namespaceuri/)-värdena.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det lokala namnet på attributet. |
| ns | [String](../../../system/string/) | Namespace-URI för attributet. |

### Returvärde

**true** om attributet hittas; annars **false**. Om **false**, ändras inte läsarens position.

## XmlReader::MoveToAttribute(int32_t) metod

När den åsidosätts i en avledd klass, flyttas den till attributet med det angivna indexet.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | **int32_t** | Indexet för attributet. |

## Se också

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)