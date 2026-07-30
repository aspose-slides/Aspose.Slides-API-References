---
title: GetAttribute()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací hodnotu atributu se zadaným názvem.
type: docs
weight: 443
url: /cs/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) metoda

Vrací hodnotu atributu se zadaným názvem.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název atributu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud atribut není nalezen, vrátí se **nullptr**.

## XmlValidatingReader::GetAttribute(String, String) metoda

Vrací hodnotu atributu se zadaným lokálním názvem a identifikátorem URI jmenného prostoru (Uniform Resource Identifier).

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud atribut není nalezen, vrátí se **nullptr**. Tato metoda nepřesune čtečku.

## XmlValidatingReader::GetAttribute(int32_t) metoda

Vrací hodnotu atributu se zadaným indexem.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | Index atributu. Index je nulový (první atribut má index 0.). |

### Návratová hodnota

Hodnota zadaného atributu.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlValidatingReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)