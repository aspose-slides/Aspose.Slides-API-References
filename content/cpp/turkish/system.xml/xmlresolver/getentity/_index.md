---
title: GetEntity()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, gerçek kaynağı içeren bir nesneye URI'yi eşler.
type: docs
weight: 14
url: /tr/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metodu

Türev bir sınıfta geçersiz kılındığında, gerçek kaynağı içeren bir nesneye URI'yi eşler.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) çağrısından döndürülen URI. |
| role | [String](../../../system/string/) | Şu anda kullanılmıyor. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Dönüş yapılacak nesnenin tipi. Mevcut sürüm yalnızca Stream nesnelerini döndürür. |

### Dönüş Değeri

Bir stream nesnesi ya da stream olmayan bir tip belirtilmişse **nullptr**.

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [XmlResolver](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)