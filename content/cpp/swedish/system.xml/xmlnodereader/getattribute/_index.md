---
title: GetAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar värdet på attributet med det angivna namnet.
type: docs
weight: 287
url: /sv/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) metod


Returnerar värdet på attributet med det angivna namnet.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på attributet. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte hittas returneras **nullptr**.

## XmlNodeReader::GetAttribute(String, String) metod


Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namnutrymmet URI för attributet. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte hittas returneras **nullptr**.

## XmlNodeReader::GetAttribute(int32_t) metod


Returnerar värdet på attributet med det angivna indexet.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | Indexet för attributet. Indexet är nollbaserat. (Det första attributet har index 0.) |

### Returvärde

Värdet på det angivna attributet.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)