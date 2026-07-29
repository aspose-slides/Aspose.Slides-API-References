---
title: GetAttribute()
second_title: Aspose.Slides för C++ API-referens
description: "När den åsidosätts i en härledd klass, hämtar den värdet på attributet med det angivna XmlReader::get_Name värdet."
type: docs
weight: 599
url: /sv/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) metod

När den åsidosätts i en härledd klass, hämtar den värdet på attributet med det angivna [XmlReader::get_Name](../get_name/)-värdet.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på attributet. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte finns eller värdet är [String::Empty](../../../system/string/empty/), **nullptr** returneras.

## XmlReader::GetAttribute(String, String) metod

När den åsidosätts i en härledd klass, hämtar den värdet på attributet med de angivna [XmlReader::get_LocalName](../get_localname/)- och [XmlReader::get_NamespaceURI](../get_namespaceuri/)-värdena.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namnutrymmet URI för attributet. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte finns eller värdet är [String::Empty](../../../system/string/empty/), **nullptr** returneras. Denna metod flyttar inte läsaren.

## XmlReader::GetAttribute(int32_t) metod

När den åsidosätts i en härledd klass, hämtar den värdet på attributet med det angivna indexet.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | **int32_t** | Indexet för attributet. Indexet är nollbaserat. (Det första attributet har index 0.) |

### Returvärde

Värdet på det angivna attributet. Denna metod flyttar inte läsaren.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)