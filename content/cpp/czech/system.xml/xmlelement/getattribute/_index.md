---
title: GetAttribute()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací hodnotu atributu se zadaným názvem.
type: docs
weight: 209
url: /cs/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) metoda


Vrací hodnotu atributu se zadaným názvem.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název atributu, který se má získat. Jedná se o kvalifikovaný název. Porovnává se s hodnotou **get_Name** odpovídajícího uzlu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud není nalezen odpovídající atribut nebo pokud atribut nemá určenou nebo výchozí hodnotu, vrátí se prázdný řetězec.

## XmlElement::GetAttribute(String, String) metoda


Vrací hodnotu atributu se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název atributu, který se má získat. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu, který se má získat. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud není nalezen odpovídající atribut nebo pokud atribut nemá určenou nebo výchozí hodnotu, vrátí se prázdný řetězec.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlElement](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)