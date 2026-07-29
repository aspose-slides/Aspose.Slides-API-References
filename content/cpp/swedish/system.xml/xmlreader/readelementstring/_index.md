---
title: ReadElementString()
second_title: Aspose.Slides för C++ API-referens
description: "Läser ett element som endast innehåller text. Det rekommenderas dock att använda XmlReader::ReadElementContentAsString-metoden istället, eftersom den ger ett mer enkelriktat sätt att hantera denna operation."
type: docs
weight: 859
url: /sv/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() metod

Läser ett element som endast innehåller text. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](../readelementcontentasstring/)-metoden istället, eftersom den ger ett mer enkelriktat sätt att hantera detta.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Returvärde

Texten som finns i elementet som lästes. En tom sträng om elementet är tomt.

## XmlReader::ReadElementString(String) metod

Kontrollerar att [XmlReader::get_Name](../get_name/)-värdet för det hittade elementet matchar den angivna strängen innan ett element som endast innehåller text läses. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](../readelementcontentasstring/)-metoden istället, eftersom den ger ett mer enkelriktat sätt att hantera detta.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet att kontrollera. |

### Returvärde

Texten som finns i elementet som lästes. En tom sträng om elementet är tomt.

## XmlReader::ReadElementString(String, String) metod

Kontrollerar att [XmlReader::get_LocalName](../get_localname/)- och [XmlReader::get_NamespaceURI](../get_namespaceuri/)-värdena för det hittade elementet matchar de angivna strängarna innan ett element som endast innehåller text läses. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](../readelementcontentasstring/)-metoden istället, eftersom den ger ett mer enkelriktat sätt att hantera detta.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Det lokala namnet att kontrollera. |
| ns | [String](../../../system/string/) | Namnområdets URI att kontrollera. |

### Returvärde

Texten som finns i elementet som lästes. En tom sträng om elementet är tomt.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)