---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ada sahip özniteliğe geçer.
type: docs
weight: 456
url: /tr/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) yöntemi

Belirtilen ada sahip özniteliğe geçer.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özniteliğin nitelikli adı. |

### Dönüş Değeri

**true** öznitelik bulunursa; aksi takdirde **false**. **false** ise, okuyucunun konumu değişmez.

## XmlValidatingReader::MoveToAttribute(String, String) yöntemi

Belirtilen yerel ada ve ad alanı Evrensel Kaynak Tanımlayıcısı (URI) olan özniteliğe geçer.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Özniteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özniteliğin ad alanı URI'si. |

### Dönüş Değeri

**true** öznitelik bulunursa; aksi takdirde **false**. **false** ise, okuyucunun konumu değişmez.

## XmlValidatingReader::MoveToAttribute(int32_t) yöntemi

Belirtilen dizine sahip özniteliğe geçer.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | **int32_t** | Özniteliğin dizini. |

## Bkz

* Sınıf [String](../../../system/string/)
* Sınıf [XmlValidatingReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)