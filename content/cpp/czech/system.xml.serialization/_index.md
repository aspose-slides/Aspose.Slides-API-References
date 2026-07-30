---
title: "System::Xml::Serialization"
second_title: Aspose.Slides pro C++ – referenční příručka API
description: 
type: docs
weight: 1158
url: /cs/system.xml.serialization/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [IXmlSerializable](./ixmlserializable/) | Poskytuje vlastní formátování pro XML serializaci a deserializaci. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [XmlAttributeOverrides](./xmlattributeoverrides/) | Umožňuje přepsání atributů, když se používá [XmlSerializer](./xmlserializer/) k serializaci nebo deserializaci objektu. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [XmlRootAttribute](./xmlrootattribute/) | Označuje cílový atribut jako kořenový element XML a řídí jeho XML serializaci. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [XmlSerializationReader](./xmlserializationreader/) | Služební třída zlepšující zkušenost s [XmlReader](../system.xml/xmlreader/). |
| [XmlSerializationWriter](./xmlserializationwriter/) | Služební třída zlepšující zkušenost s [XmlWriter](../system.xml/xmlwriter/). |
| [XmlSerializer](./xmlserializer/) | Provádí serializaci a deserializaci objektů do a z XML dokumentů. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [XmlSerializerImplementation](./xmlserializerimplementation/) | Interní třída pro použití s [XmlSerializer](./xmlserializer/). |
| [XmlSerializerNamespaces](./xmlserializernamespaces/) | Obsahuje XML jmenné prostory a předpony, které [Serialization::XmlSerializer](./xmlserializer/) používá k vytváření kvalifikovaných názvů v instanci XML dokumentu. |