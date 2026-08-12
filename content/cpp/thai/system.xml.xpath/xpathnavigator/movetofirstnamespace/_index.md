---
title: MoveToFirstNamespace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อทำการ override ในคลาสที่สืบทอด จะย้าย XPathNavigator ไปยังโหนดเนมสเปซแรกที่ตรงกับ XPathNamespaceScope ที่ระบุ
type: docs
weight: 560
url: /th/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) เมธอด

When overridden in a derived class, moves the [XPathNavigator](../) to the first namespace node that matches the XPathNamespaceScope specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | ค่า XPathNamespaceScope ที่อธิบายขอบเขตของเนมสเปซ |

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) การย้ายไปยังโหนดเนมสเปซแรกสำเร็จ; มิฉะนั้น **false**. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## XPathNavigator::MoveToFirstNamespace() เมธอด

Moves the [XPathNavigator](../) to first namespace node of the current node.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) การย้ายไปยังโหนดเนมสเปซแรกสำเร็จ; มิฉะนั้น **false**. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## ดูเพิ่มเติม

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)