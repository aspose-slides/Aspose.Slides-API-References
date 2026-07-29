---
title: CreateXmlDeclaration()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en XmlDeclaration-nod med de angivna värdena.
type: docs
weight: 378
url: /sv/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) method

Skapar en [XmlDeclaration](../../xmldeclaration/) nod med de angivna värdena.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | Versionen måste vara "1.0". |
| encoding | const [String](../../../system/string/)\& | Värdet för kodningsattributet. Detta är den kodning som används när du sparar [XmlDocument](../) till en fil eller en ström; därför måste den sättas till en sträng som stöds av klassen [Text::Encoding](../../../system.text/encoding/), annars misslyckas "XmlDocument::Save(String)". Om detta är **nullptr** eller [String::Empty](../../../system/string/empty/) skriver [XmlDocument::Save](../save/)-metoden inte ett kodningsattribut i XML-deklarationen och därför används standardkodningen UTF-8. |
| standalone | const [String](../../../system/string/)\& | Värdet måste vara antingen "yes" eller "no". Om detta är **nullptr** eller [String::Empty](../../../system/string/empty/) skriver [XmlDocument::Save](../save/)-metoden inte ett fristående attribut i XML-deklarationen. |

### Returvärde

Den nya [XmlDeclaration](../../xmldeclaration/)-noden.

## Anmärkningar

Obs: Om [XmlDocument](../) sparas till antingen en TextWriter eller en [XmlTextWriter](../../xmltextwriter/) så ignoreras detta kodningsvärde. Istället används kodningen för TextWriter eller [XmlTextWriter](../../xmltextwriter/). Detta säkerställer att den skriven XML kan läsas tillbaka med rätt kodning.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [XmlDeclaration](../../xmldeclaration/)
* Klass [String](../../../system/string/)
* Klass [XmlDocument](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)