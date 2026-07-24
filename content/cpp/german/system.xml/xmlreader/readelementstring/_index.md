---
title: ReadElementString()
second_title: Aspose.Slides für C++ API-Referenz
description: "Liest ein ausschließlich Text-Element. Es wird jedoch empfohlen, stattdessen die XmlReader::ReadElementContentAsString Methode zu verwenden, da sie eine einfachere Möglichkeit bietet, diesen Vorgang zu handhaben."
type: docs
weight: 859
url: /de/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() Methode

Liest ein ausschließlich Text-Element. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) Methode zu verwenden, da sie eine einfachere Möglichkeit bietet, diesen Vorgang zu handhaben.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Rückgabewert

Der Text, der im gelesenen Element enthalten ist. Ein leerer String, wenn das Element leer ist.

## XmlReader::ReadElementString(String) Methode

Prüft, ob der [XmlReader::get_Name](../get_name/) Wert des gefundenen Elements mit dem angegebenen String übereinstimmt, bevor ein ausschließlich Text-Element gelesen wird. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) Methode zu verwenden, da sie eine einfachere Möglichkeit bietet, diesen Vorgang zu handhaben.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der zu prüfende Name. |

### Rückgabewert

Der Text, der im gelesenen Element enthalten ist. Ein leerer String, wenn das Element leer ist.

## XmlReader::ReadElementString(String, String) Methode

Prüft, ob die [XmlReader::get_LocalName](../get_localname/) und [XmlReader::get_NamespaceURI](../get_namespaceuri/) Werte des gefundenen Elements mit den angegebenen Strings übereinstimmen, bevor ein ausschließlich Text-Element gelesen wird. Es wird jedoch empfohlen, stattdessen die [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) Methode zu verwenden, da sie eine einfachere Möglichkeit bietet, diesen Vorgang zu handhaben.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Der zu prüfende lokale Name. |
| ns | [String](../../../system/string/) | Der zu prüfende Namespace-URI. |

### Rückgabewert

Der Text, der im gelesenen Element enthalten ist. Ein leerer String, wenn das Element leer ist.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)