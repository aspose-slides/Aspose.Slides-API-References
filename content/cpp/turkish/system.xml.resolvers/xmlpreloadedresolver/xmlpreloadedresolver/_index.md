---
title: XmlPreloadedResolver()
second_title: Aspose.Slides for C++ API Referansı
description: XmlPreloadedResolver sınıfının yeni bir örneğini başlatır.
type: docs
weight: 27
url: /tr/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() yapıcı

Yeni bir [XmlPreloadedResolver](../) sınıfı örneği başlatır.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) yapıcı

Belirtilen önceden yüklenmiş iyi bilinen DTD'ler ile yeni bir [XmlPreloadedResolver](../) sınıfı örneği başlatır.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Önceden doldurulması gereken iyi bilinen DTD'ler. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) yapıcı

Belirtilen geri dönüş çözücüsü ile yeni bir [XmlPreloadedResolver](../) sınıfı örneği başlatır.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) veya kendi çözücünüz. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) yapıcı

Belirtilen geri dönüş çözücüsü ve önceden yüklenmiş iyi bilinen DTD'ler ile yeni bir [XmlPreloadedResolver](../) sınıfı örneği başlatır.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) veya kendi çözücünüz. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Önceden doldurulması gereken iyi bilinen DTD'ler. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) yapıcı

Belirtilen geri dönüş çözücüsü, önceden yüklenmiş iyi bilinen DTD'ler ve URI eşitlik karşılaştırıcısı ile yeni bir [XmlPreloadedResolver](../) sınıfı örneği başlatır.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) veya kendi çözücünüz. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Önceden doldurulması gereken iyi bilinen DTD'ler. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | URI'leri karşılaştırırken kullanılacak IEqualityComparer arayüzünün uygulanması. |

## Ayrıca Bakınız

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlPreloadedResolver](../)
* Sınıf [XmlResolver](../../../system.xml/xmlresolver/)
* Sınıf [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Sınıf [Uri](../../../system/uri/)
* Ad alanı [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)