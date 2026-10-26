---
title: ReadElementString()
second_title: Aspose.Slides voor C++ API-referentie
description: "Leest een element dat alleen tekst bevat. Het wordt echter aanbevolen om in plaats daarvan de XmlReader::ReadElementContentAsString methode te gebruiken, omdat deze een meer directe manier biedt om deze bewerking af te handelen."
type: docs
weight: 859
url: /nl/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() methode

Leest een element dat alleen tekst bevat. Het wordt echter aanbevolen om de [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) methode te gebruiken, omdat deze een meer directe manier biedt om deze bewerking af te handelen.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Retourwaarde

De tekst die zich in het gelezen element bevindt. Een lege string als het element leeg is.

## XmlReader::ReadElementString(String) methode

Controleert of de [XmlReader::get_Name](../get_name/) waarde van het gevonden element overeenkomt met de opgegeven string voordat een element dat alleen tekst bevat wordt gelezen. Het wordt echter aanbevolen om de [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) methode te gebruiken, omdat deze een meer directe manier biedt om deze bewerking af te handelen.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De te controleren naam. |

### Retourwaarde

De tekst die zich in het gelezen element bevindt. Een lege string als het element leeg is.

## XmlReader::ReadElementString(String, String) methode

Controleert of de [XmlReader::get_LocalName](../get_localname/) en [XmlReader::get_NamespaceURI](../get_namespaceuri/) waarden van het gevonden element overeenkomen met de opgegeven strings voordat een element dat alleen tekst bevat wordt gelezen. Het wordt echter aanbevolen om de [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) methode te gebruiken, omdat deze een meer directe manier biedt om deze bewerking af te handelen.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localname | [String](../../../system/string/) | De te controleren lokale naam. |
| ns | [String](../../../system/string/) | De te controleren namespace-URI. |

### Retourwaarde

De tekst die zich in het gelezen element bevindt. Een lege string als het element leeg is.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)