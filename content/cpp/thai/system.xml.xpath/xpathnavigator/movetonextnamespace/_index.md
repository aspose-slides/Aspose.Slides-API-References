---
title: MoveToNextNamespace()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เมื่อมีการเขียนทับในคลาสที่สืบทอด จะย้าย XPathNavigator ไปยังโหนดเนมสแพซถัดไปที่ตรงกับ XPathNamespaceScope ที่ระบุ
type: docs
weight: 573
url: /th/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) method

เมื่อมีการเขียนทับในคลาสที่สืบทอด, จะย้าย [XPathNavigator](../) ไปยังโหนดเนมสแพซถัดไปที่ตรงกับ XPathNamespaceScope ที่ระบุ

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | ค่าชนิด XPathNamespaceScope ที่บ่งบอกขอบเขตของเนมสแพซ |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNextNamespace() method

ย้าย [XPathNavigator](../) ไปยังโหนดเนมสแพซถัดไป

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* คลาส [XPathNavigator](../)
* เนมสแพซ [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)