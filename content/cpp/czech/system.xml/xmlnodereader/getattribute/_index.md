---
title: GetAttribute()
second_title: Aspose.Slides pro C++ referenci API
description: Vrací hodnotu atributu se zadaným názvem.
type: docs
weight: 287
url: /cs/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) metoda

Vrací hodnotu atributu se zadaným názvem.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název atributu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud atribut není nalezen, **nullptr** je vráceno.

## XmlNodeReader::GetAttribute(String, String) metoda

Vrací hodnotu atributu se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokální název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud atribut není nalezen, **nullptr** je vráceno.

## XmlNodeReader::GetAttribute(int32_t) metoda

Vrací hodnotu atributu se zadaným indexem.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| attributeIndex | **int32_t** | Index atributu. Index je nulově založený. (První atribut má index 0.) |

### Návratová hodnota

Hodnota zadaného atributu.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)