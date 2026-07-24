---
title: ResolveUri()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, temel ve göreli URI'lerden mutlak URI'yi çözer.
type: docs
weight: 27
url: /tr/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) metodu


Türetilmiş bir sınıfta geçersiz kılındığında, temel ve göreli URI'lardan mutlak URI'yi çözer.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Göreli URI'yı çözmek için kullanılan temel URI. |
| relativeUri | [String](../../../system/string/) | Çözülecek URI. URI mutlak veya göreli olabilir. Mutlak ise, bu değer **baseUri** değerini etkili bir şekilde değiştirir. Göreli ise, mutlak bir URI oluşturmak için **baseUri** ile birleştirilir. |

### Dönüş Değeri

Mutlak URI veya göreli URI çözülemezse **nullptr**.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlResolver](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)