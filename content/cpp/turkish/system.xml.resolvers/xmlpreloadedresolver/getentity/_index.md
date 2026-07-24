---
title: GetEntity()
second_title: Aspose.Slides için C++ API Referansı
description: Bir URI'yı gerçek kaynağı içeren bir nesneye eşler.
type: docs
weight: 53
url: /tr/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloaderResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metod

Bir URI'yı gerçek kaynağı içeren bir nesneye eşler.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) çağrısından döndürülen URI. |
| role | [String](../../../system/string/) | Şu anda kullanılmıyor. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Döndürülecek nesnenin türü. [XmlPreloadedResolver](../) , [String](../../../system/string/) olarak eklenen URI'lar için Stream nesnelerini ve TextReader nesnelerini destekler. İstenilen tür çözücü tarafından desteklenmiyorsa bir istisna fırlatılacaktır. Bu çözücünün belirli bir **Tür**'ı destekleyip desteklemediğini belirlemek için XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) metodunu kullanın. |

### Dönüş Değeri

Gerçek kaynağa karşılık gelen bir Stream veya TextReader nesnesi.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [XmlPreloadedResolver](../)
* Ad Alanı [System::Xml::Resolvers](../../)
* Kütüphane [Aspose.Slides](../../../)