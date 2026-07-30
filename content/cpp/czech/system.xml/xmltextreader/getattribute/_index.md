---
title: GetAttribute()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací hodnotu atributu se zadaným názvem.
type: docs
weight: 495
url: /cs/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) metoda

Vrací hodnotu atributu se zadaným názvem.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název atributu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud není atribut nalezen, **nullptr** je vrácena.

## XmlTextReader::GetAttribute(String, String) metoda

Vrací hodnotu atributu se zadaným místním názvem a URI jmenného prostoru.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Místní název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud není atribut nalezen, **nullptr** je vrácena. Tato metoda nepřesune čtečku.

## XmlTextReader::GetAttribute(int32_t) metoda

Vrací hodnotu atributu se zadaným indexem.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | **int32_t** | Index atributu. Index je nulový (indexováno od nuly). (První atribut má index 0.) |

### Návratová hodnota

Hodnota zadaného atributu.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)