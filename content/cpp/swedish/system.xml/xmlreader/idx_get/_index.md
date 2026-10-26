---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en härledd klass hämtas värdet på attributet med det angivna indexet.
type: docs
weight: 612
url: /sv/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) metod


När den åsidosätts i en härledd klass hämtas värdet på attributet med det angivna indexet.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | Attributets index. |

### Returvärde

Värdet på det angivna attributet.

## XmlReader::idx_get(String) metod


När den åsidosätts i en härledd klass hämtas värdet på attributet med det angivna [XmlReader::get_Name](../get_name/)-värdet.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på attributet. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte finns hittas, **nullptr** returneras.

## XmlReader::idx_get(String, String) metod


När den åsidosätts i en härledd klass hämtas värdet på attributet med de angivna [XmlReader::get_LocalName](../get_localname/)- och [XmlReader::get_NamespaceURI](../get_namespaceuri/)-värdena.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Attributets namnrymds-URI. |

### Returvärde

Värdet på det angivna attributet. Om attributet inte finns hittas, **nullptr** returneras.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)