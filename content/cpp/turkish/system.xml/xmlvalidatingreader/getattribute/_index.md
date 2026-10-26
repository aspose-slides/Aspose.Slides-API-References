---
title: GetAttribute()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen ada sahip özniteliğin değerini döndürür.
type: docs
weight: 443
url: /tr/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) metod

Belirtilen ada sahip özniteliğin değerini döndürür.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özniteliğin nitelikli adı. |

### Dönüş Değeri

Belirtilen öznitelğin değeri. Öznitelik bulunamazsa **nullptr** döndürülür.

## XmlValidatingReader::GetAttribute(String, String) metod

Belirtilen yerel ada ve ad alanı Evrensel Kaynak Tanımlayıcısı (URI) sahip özniteliğin değerini döndürür.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Özniteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özniteliğin ad alanı URI'si. |

### Dönüş Değeri

Belirtilen öznitelğin değeri. Öznitelik bulunamazsa **nullptr** döndürülür. Bu metod okuyucuyu hareket ettirmez.

## XmlValidatingReader::GetAttribute(int32_t) metod

Belirtilen dizine sahip özniteliğin değerini döndürür.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | **int32_t** | Özniteliğin dizini. Dizin sıfır tabanlıdır. (İlk öznitelik dizin 0'a sahiptir.) |

### Dönüş Değeri

Belirtilen öznitelğin değeri.

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [XmlValidatingReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)