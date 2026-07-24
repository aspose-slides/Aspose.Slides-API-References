---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ada sahip özniteliğe geçer.
type: docs
weight: 300
url: /tr/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) yöntemi


Belirtilen adla özniteliğe geçer.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özniteliğin nitelikli adı. |

### Return Value

**true** öznitelik bulunduysa; aksi takdirde **false**. **false** ise, okuyucunun konumu değişmez.

## XmlNodeReader::MoveToAttribute(String, String) yöntemi


Belirtilen yerel ada ve ad alanı URI'sine sahip özniteliğe geçer.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özniteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özniteliğin ad alanı URI'si. |

### Return Value

**true** öznitelik bulunduysa; aksi takdirde **false**. **false** ise, okuyucunun konumu değişmez.

## XmlNodeReader::MoveToAttribute(int32_t) yöntemi


Belirtilen dizine sahip özniteliğe geçer.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| attributeIndex | **int32_t** | Özniteliğin dizini. |

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNodeReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)