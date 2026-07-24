---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Referansı
description: Temel ve göreli URI'lerden mutlak URI'yi çözer.
type: docs
weight: 40
url: /tr/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) metodu

Temel URI ve göreli URI'lerden mutlak URI'yi çözer.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Göreli URI'yi çözmek için kullanılan temel URI. |
| relativeUri | [String](../../../system/string/) | Çözülmek istenen URI. URI mutlak ya da göreli olabilir. Mutlak ise bu değer **baseUri** değerini etkili bir şekilde değiştirir. Göreli ise **baseUri** ile birleştirilerek mutlak URI oluşturur. |

### Dönüş Değeri

Mutlak URI'yi temsil eden [Uri](../../../system/uri/) ya da göreli URI çözülemezse **nullptr**.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlPreloadedResolver](../)
* İsim Uzayı [System::Xml::Resolvers](../../)
* Kütüphane [Aspose.Slides](../../../)