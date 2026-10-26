---
title: IsStartElement()
second_title: Aspose.Slides för C++ API-referens
description: "Anropar XmlReader::MoveToContent och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg."
type: docs
weight: 885
url: /sv/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() metod

Anropar [XmlReader::MoveToContent](../movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Returvärde

**true** om [XmlReader::MoveToContent](../movetocontent/) hittar en starttagg eller en tom elementtagg; **false** om en nodtyp annan än [XmlNodeType::Element](../../xmlnodetype/) hittades.

## XmlReader::IsStartElement(String) metod

Anropar [XmlReader::MoveToContent](../movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg och om [XmlReader::get_Name](../get_name/)-värdet för det hittade elementet matchar det angivna argumentet.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Strängen som matchas mot **Name**-värdet för det hittade elementet. |

### Returvärde

**true** om den resulterande noden är ett element och **Name**-värdet matchar den angivna strängen. **false** om en nodtyp annan än [XmlNodeType::Element](../../xmlnodetype/) hittades eller om elementets **Name**-värde inte matchar den angivna strängen.

## XmlReader::IsStartElement(String, String) metod

Anropar [XmlReader::MoveToContent](../movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg och om [XmlReader::get_LocalName](../get_localname/)- och [XmlReader::get_NamespaceURI](../get_namespaceuri/)-värdena för det hittade elementet matchar de angivna strängarna.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Strängen som ska matchas mot **LocalName**-värdet för det hittade elementet. |
| ns | [String](../../../system/string/) | Strängen som ska matchas mot **NamespaceURI**-värdet för det hittade elementet. |

### Returvärde

**true** om den resulterande noden är ett element. **false** om en nodtyp annan än [XmlNodeType::Element](../../xmlnodetype/) hittades eller om **LocalName**- och **NamespaceURI**-värdena för elementet inte matchar de angivna strängarna.

## Se även

* Klass [XmlReader](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)