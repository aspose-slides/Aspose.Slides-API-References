---
title: GetProductLength()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แปลงสตริงที่ส่งเข้ามาตั้งแต่ตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส ProductHeaderValue.
type: docs
weight: 105
url: /th/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาตั้งแต่ตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส [ProductHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่จะทำการแยก |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยก |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | อินสแตนซ์ที่จะกำหนดวัตถุที่แยกได้ |

### ค่าที่ส่งคืน

ส่งคืนความยาวของสตริงย่อยที่แยกได้, มิฉะนั้นจะเป็น 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ProductHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)