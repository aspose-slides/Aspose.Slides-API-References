---
title: XmlPreloadedResolver()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่ของคลาส XmlPreloadedResolver
type: docs
weight: 27
url: /th/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](../) ด้วย DTD ที่เป็นที่รู้จักและโหลดล่วงหน้าตามที่ระบุ.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD ที่เป็นที่รู้จักซึ่งควรจะเติมล่วงหน้าไปยังแคช. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](../) ด้วยรีโซลเวอร์สำรองที่ระบุ.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) หรือรีโซลเวอร์ของคุณเอง. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](../) ด้วยรีโซลเวอร์สำรองที่ระบุและ DTD ที่เป็นที่รู้จักและโหลดล่วงหน้า.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) หรือรีโซลเวอร์ของคุณเอง. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD ที่เป็นที่รู้จักซึ่งควรจะเติมล่วงหน้าไปยังแคช. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [XmlPreloadedResolver](../) ด้วยรีโซลเวอร์สำรองที่ระบุ, DTD ที่เป็นที่รู้จักและโหลดล่วงหน้า, และตัวเปรียบเทียบความเท่าเทียม URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) หรือรีโซลเวอร์ของคุณเอง. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD ที่เป็นที่รู้จักซึ่งควรจะเติมล่วงหน้าไปยังแคช. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | การนำไปใช้ของอินเตอร์เฟซ IEqualityComparer เพื่อใช้เมื่อคุณเปรียบเทียบ URI. |

## ดูเพิ่มเติม

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)