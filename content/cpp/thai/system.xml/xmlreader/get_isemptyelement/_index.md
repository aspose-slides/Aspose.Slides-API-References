---
title: get_IsEmptyElement()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อทำการ override ในคลาสที่สืบทอด จะได้ค่าที่บ่งชี้ว่าปัจจุบันโหนดเป็นอิลิเมนท์ที่ว่างเปล่า (เช่น <MyElement/>).
type: docs
weight: 131
url: /th/system.xml/xmlreader/get_isemptyelement/
---
## XmlReader::get_IsEmptyElement() เมธอด

เมื่อทำการ override ในคลาสที่สืบทอด ได้ค่าที่บ่งชี้ว่าปัจจุบันโหนดเป็นอิลิเมนท์ที่ว่างเปล่า (เช่น **<MyElement/>**)

```cpp
virtual bool System::Xml::XmlReader::get_IsEmptyElement()=0
```

### ค่าที่ส่งกลับ

**true** ถ้าโหนดปัจจุบันเป็นอิลิเมนท์ ([XmlReader::get_NodeType](../get_nodetype/) เท่ากับ [XmlNodeType::Element](../../xmlnodetype/)) ที่ลงท้ายด้วย **/>**; มิฉะนั้น **false**.

## ดูเพิ่มเติม

* คลาส [XmlReader](../)
* เนมส페ซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)