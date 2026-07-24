---
title: SupportsType()
second_title: Aspose.Slides için C++ API Referansı
description: Çözümleyicinin yalnızca Stream dışındaki diğer Types'ı destekleyip desteklemediğini belirler.
type: docs
weight: 66
url: /tr/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method


Çözümleyicinin yalnızca Stream dışındaki diğer Types'ı destekleyip desteklemediğini belirler.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Kontrol edilecek mutlak URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Döndürülecek Type. |

### Dönüş Değeri

**true** if the Type is supported; otherwise, **false**.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [XmlPreloadedResolver](../)
* Ad Alanı [System::Xml::Resolvers](../../)
* Kütüphane [Aspose.Slides](../../../)