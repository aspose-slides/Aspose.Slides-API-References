---
title: idx_get()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací atribut se zadaným indexem.
type: docs
weight: 1
url: /cs/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) metoda


Vrací atribut se zadaným indexem.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | **int32_t** | Index atributu. |

### Návratová hodnota

Atribut na zadaném indexu.

## XmlAttributeCollection::idx_get(const String\&) metoda


Vrací atribut se zadaným názvem.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kvalifikovaný název atributu. |

### Návratová hodnota

Atribut se zadaným názvem. Pokud atribut neexistuje, tato metoda vrátí **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) metoda


Vrací atribut se zadaným lokálním názvem a Uniform Resource Identifier (URI) jmenného prostoru.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Lokální název atributu. |
| namespaceURI | const [String](../../../system/string/)\& | URI jmenného prostoru atributu. |

### Návratová hodnota

Atribut se zadaným lokálním názvem a URI jmenného prostoru. Pokud atribut neexistuje, tato metoda vrátí **nullptr**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlAttribute](../../xmlattribute/)
* Třída [XmlAttributeCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)