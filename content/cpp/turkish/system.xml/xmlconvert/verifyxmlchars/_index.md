---
title: VerifyXmlChars()
second_title: Aspose.Slides for C++ API Referansı
description: Dize argümanındaki tüm karakterler ve surrogate çift karakterler geçerli XML karakterleri ise, verilen dize döndürülür; aksi takdirde, karşılaşılan ilk geçersiz karakter hakkında bilgi içeren bir XmlException fırlatılır.
type: docs
weight: 105
url: /tr/system.xml/xmlconvert/verifyxmlchars/
---
## XmlConvert::VerifyXmlChars(const String\&) metodu

Geçerli XML karakterleri olmayan ilk karakterle ilgili bilgi ile bir XmlException fırlatılır; aksi takdirde, dize argümanındaki tüm karakterler ve surrogate çift karakterler geçerli XML karakterleri ise, verilen dize döndürülür.

```cpp
static String System::Xml::XmlConvert::VerifyXmlChars(const String &content)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| content | const [String](../../../system/string/)\& | [String](../../../system/string/) doğrulanacak karakterleri içeren |

### Dönüş Değeri

Geçerli XML karakterleri olmayan ilk karakterle ilgili bilgi ile bir XmlException fırlatılır; aksi takdirde, dize argümanındaki tüm karakterler ve surrogate çift karakterler geçerli XML karakterleri ise, verilen dize döndürülür.

## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlConvert](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)