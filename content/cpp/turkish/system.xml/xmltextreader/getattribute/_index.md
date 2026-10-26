---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ada sahip özniteliğin değerini döndürür.
type: docs
weight: 495
url: /tr/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) yöntemi


Belirtilen ada sahip özniteliğin değerini döndürür.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özniteliğin nitelikli adı. |

### Dönüş Değeri

Belirtilen özniteliğin değeri. Öznitelik bulunamazsa **nullptr** döndürülür.

## XmlTextReader::GetAttribute(String, String) yöntemi


Belirtilen yerel ada ve ad alanı URI'sine sahip özniteliğin değerini döndürür.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Özniteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özniteliğin ad alanı URI'si. |

### Dönüş Değeri

Belirtilen özniteliğin değeri. Öznitelik bulunamazsa **nullptr** döndürülür. Bu yöntem okuyucuyu hareket ettirmez.

## XmlTextReader::GetAttribute(int32_t) yöntemi


Belirtilen dizine sahip özniteliğin değerini döndürür.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | **int32_t** | Özniteliğin dizini. Dizin sıfır temellidir. (İlk öznitelik dizin 0'a sahiptir.) |

### Dönüş Değeri

Belirtilen özniteliğin değeri.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlTextReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)