---
title: WriteStartElement()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass skriver den angivna starttaggen och associerar den med den angivna namnrymden.
type: docs
weight: 92
url: /sv/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) metod


När den åsidosätts i en avledd klass skriver den angiven starttagg och associerar den med den angivna namnrymden.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på elementet. |
| ns | const [String](../../../system/string/)\& | URI:n för namnrymden att associera med elementet. Om denna namnrymd redan är i räckvidd och har ett associerat prefix skriver skrivaren automatiskt även det prefixet. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) metod


När den åsidosätts i en avledd klass skriver den angiven starttagg och associerar den med den angivna namnrymden och prefixet.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Namnrymdsprefixet för elementet. |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på elementet. |
| ns | const [String](../../../system/string/)\& | URI:n för namnrymden att associera med elementet. |

## XmlWriter::WriteStartElement(const String\&) metod


När den åsidosätts i en avledd klass skriver den ut en starttagg med det angivna lokala namnet.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på elementet. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlWriter](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)