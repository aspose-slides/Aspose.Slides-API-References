---
title: get_Encoding()
second_title: Aspose.Slides for C++ API Referansı
description: XML belgesinin kodlama seviyesini döndürür.
type: docs
weight: 14
url: /tr/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() metodu


XML belgesinin kodlama seviyesini döndürür.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### Dönüş Değeri

Geçerli karakter kodlama adı.
## Açıklamalar



XML için en yaygın olarak desteklenen karakter kodlama adları şunlardır: 

| Kategori | Kodlama Adları |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n ("n" 1 ile 9 arasında bir rakamdır) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |


Bu değer isteğe bağlıdır. Bir değer ayarlanmamışsa, bu metot [String::Empty](../../../system/string/empty/) döndürür. Bir kodlama özniteliği eklenmemişse, belge yazıldığında veya kaydedildiğinde UTF-8 kodlaması varsayılır. 
## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlDeclaration](../)
* İsim Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)