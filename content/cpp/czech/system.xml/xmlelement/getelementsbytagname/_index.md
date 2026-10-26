---
title: GetElementsByTagName()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Vrací XmlNodeList obsahující seznam všech podřízených elementů, které odpovídají zadanému XmlElement::get_Name."
type: docs
weight: 287
url: /cs/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) metoda


Vrací [XmlNodeList](../../xmlnodelist/) obsahující seznam všech podřízených elementů, které odpovídají zadanému [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název značky, který se má porovnat. Jedná se o kvalifikovaný název. Porovnává se s hodnotou **get_Name** odpovídajícího uzlu. Hvězdička (*) je speciální hodnota, která odpovídá všem značkám. |

### Návratová hodnota

[XmlNodeList](../../xmlnodelist/) obsahující seznam všech odpovídajících uzlů. Seznam je prázdný, pokud neexistují žádné odpovídající uzly.

## XmlElement::GetElementsByTagName(String, String) metoda


Vrací [XmlNodeList](../../xmlnodelist/) obsahující seznam všech podřízených elementů, které odpovídají zadaným [XmlElement::get_LocalName](../get_localname/) a [XmlElement::get_NamespaceURI](../get_namespaceuri/) hodnotám.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Místní název, který se má porovnat. Hvězdička (*) je speciální hodnota, která odpovídá všem značkám. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru, který se má porovnat. |

### Návratová hodnota

[XmlNodeList](../../xmlnodelist/) obsahující seznam všech odpovídajících uzlů. Seznam je prázdný, pokud neexistují žádné odpovídající uzly.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNodeList](../../xmlnodelist/)
* Třída [String](../../../system/string/)
* Třída [XmlElement](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)