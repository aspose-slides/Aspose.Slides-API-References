---
title: GetEntity()
second_title: Aspose.Slides for C++ API Referansı
description: Gerçek kaynağı içeren bir nesneye URI eşler.
type: docs
weight: 27
url: /tr/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metod

Bir URI'yi gerçek kaynağı içeren bir nesneye eşler.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) çağrısından döndürülen URI. |
| role | [String](../../../system/string/) | Şu anda kullanılmıyor. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Döndürülecek nesnenin türü. Mevcut sürüm yalnızca Stream nesnelerini döndürür. |

### Dönüş Değeri

Alttaki [XmlResolver](../../xmlresolver/) üzerinde **GetEntity** çağrılarak döndürülen akış. Stream dışındaki bir tür belirtilirse, metod **nullptr** döndürür.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [XmlSecureResolver](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)