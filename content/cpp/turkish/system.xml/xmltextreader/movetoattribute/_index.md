---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ada sahip özniteliğe geçer.
type: docs
weight: 508
url: /tr/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) yöntemi

Belirtilen ada sahip özniteliğe geçer.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Öznitelğin nitelikli adı. |

### Dönüş Değeri

**true** öznitelik bulunursa; aksi halde **false**. **false** ise, okuyucunun konumu değişmez.

## XmlTextReader::MoveToAttribute(String, String) yöntemi

Belirtilen yerel ada ve ad alanı URI'sine sahip özniteliğe geçer.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Öznitelğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Öznitelğin ad alanı URI'si. |

### Dönüş Değeri

**true** öznitelik bulunursa; aksi halde **false**. **false** ise, okuyucunun konumu değişmez.

## XmlTextReader::MoveToAttribute(int32_t) yöntemi

Belirtilen indeks'e sahip özniteliğe geçer.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | **int32_t** | Öznitelğin indeksi. |

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlTextReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)