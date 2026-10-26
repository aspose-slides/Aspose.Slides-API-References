---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Referansı
description: Altındaki XmlResolver üzerinde ResolveUri çağrısı yaparak temel ve göreceli URI'lardan mutlak URI'yı çözer.
type: docs
weight: 40
url: /tr/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) metodu


Temel ve göreceli URI'lardan mutlak URI'yı, altındaki [XmlResolver](../../xmlresolver/) üzerinde **ResolveUri** çağırarak çözer.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Temel URI, göreceli URI'yı çözmek için kullanılır. |
| relativeUri | [String](../../../system/string/) | Çözülecek URI. URI mutlak veya göreceli olabilir. Mutlak ise bu değer **baseUri** değerini etkili bir şekilde değiştirir. Göreceli ise **baseUri** ile birleşerek mutlak bir URI oluşturur. |

### Dönüş Değeri

Mutlak URI veya **nullptr** eğer göreceli URI çözülemezse (altındaki [XmlResolver](../../xmlresolver/) üzerinde **ResolveUri** çağırılarak döndürülür).

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlSecureResolver](../)
* İsim Uzayı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)