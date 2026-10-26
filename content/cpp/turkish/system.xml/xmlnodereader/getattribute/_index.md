---
title: GetAttribute()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen ada sahip özelliğin değerini döndürür.
type: docs
weight: 287
url: /tr/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) yöntemi

Belirtilen ada sahip özelliğin değerini döndürür.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özelliğin nitelikli adı. |

### Dönüş Değeri

Belirtilen özelliğin değeri. Özellik bulunamazsa **nullptr** döndürülür.

## XmlNodeReader::GetAttribute(String, String) yöntemi

Belirtilen yerel ada ve ad alanı URI'sine sahip özelliğin değerini döndürür.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özelliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özelliğin ad alanı URI'si. |

### Dönüş Değeri

Belirtilen özelliğin değeri. Özellik bulunamazsa **nullptr** döndürülür.

## XmlNodeReader::GetAttribute(int32_t) yöntemi

Belirtilen dizine sahip özelliğin değerini döndürür.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| attributeIndex | **int32_t** | Özelliğin dizini. Dizin sıfır temellidir. (İlk özelliğin dizini 0'dır.) |

### Dönüş Değeri

Belirtilen özelliğin değeri.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNodeReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)