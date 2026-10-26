---
title: Item()
second_title: Aspose.Slides for C++ เอกสารอ้างอิง API
description: ดึงโหนดที่ตำแหน่งดัชนีที่ระบุใน XmlNamedNodeMap.
type: docs
weight: 53
url: /th/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) เมธอด

คืนค่าโหนดที่ตำแหน่งดัชนีที่ระบุใน [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งดัชนีของโหนดที่จะดึงจาก [XmlNamedNodeMap](../). ดัชนีเริ่มจากศูนย์; ดังนั้นดัชนีของโหนดแรกคือ 0 และดัชนีของโหนดสุดท้ายคือ [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Return Value

[XmlNode](../../xmlnode/) ที่ตำแหน่งดัชนีที่ระบุ หาก **index** มีค่าน้อยกว่า 0 หรือมากกว่าหรือเท่ากับค่า [XmlNamedNodeMap::get_Count](../get_count/) จะคืนค่า **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)