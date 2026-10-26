---
title: ResolveUri()
second_title: Aspose.Slides için C++ API Referansı
description: Temel ve göreceli URI'lerden mutlak URI'yi çözer.
type: docs
weight: 66
url: /tr/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) yöntemi

Temel ve göreceli URI'lerden mutlak URI'yi çözer.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Göreceli URI'yi çözmek için kullanılan temel URI. |
| relativeUri | [String](../../../system/string/) | Çözülecek URI. URI mutlak veya göreceli olabilir. Mutlak ise bu değer **baseUri** değerini etkili bir şekilde değiştirir. Göreceli ise **baseUri** ile birleştirilerek mutlak URI oluşturulur. |

### Return Value

Mutlak URI, ya da göreceli URI çözülemezse **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlUrlResolver](../)
* Ad alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)