---
title: SetAttribute()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastaví hodnotu atributu se zadaným názvem.
type: docs
weight: 222
url: /cs/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) metoda


Nastaví hodnotu atributu se zadaným názvem.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název atributu, který se má vytvořit nebo upravit. Jedná se o kvalifikovaný název. Pokud název obsahuje dvojtečku, je rozdělen na předponu a komponentu lokálního názvu. |
| value | [String](../../../system/string/) | Hodnota, která má být nastavena pro atribut. |

## XmlElement::SetAttribute(String, String, String) metoda


Nastaví hodnotu atributu se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |
| value | [String](../../../system/string/) | Hodnota, která má být nastavena pro atribut. |

### Návratová hodnota

Hodnota atributu.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlElement](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)