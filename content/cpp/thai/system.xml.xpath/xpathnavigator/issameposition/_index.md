---
title: IsSamePosition()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เมื่อทำการโอเวอร์ไรด์ในคลาสที่สืบทอด, กำหนดว่าปัจจุบัน XPathNavigator อยู่ในตำแหน่งเดียวกับ XPathNavigator ที่ระบุหรือไม่.
type: docs
weight: 716
url: /th/system.xml.xpath/xpathnavigator/issameposition/
---
## XPathNavigator::IsSamePosition(SharedPtr\<XPathNavigator\>) เมธอด

When overridden in a derived class, determines whether the current [XPathNavigator](../) is at the same position as the specified [XPathNavigator](../).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::IsSamePosition(SharedPtr<XPathNavigator> other)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | [XPathNavigator](../) ที่จะเปรียบเทียบกับ [XPathNavigator](../) นี้. |

### ค่าที่ส่งคืน

**true** หากวัตถุ [XPathNavigator](../) ทั้งสองมีตำแหน่งเดียวกัน; มิฉะนั้น, **false**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)