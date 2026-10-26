---
title: GetProductInfoLength()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ส่งเข้ามาตั้งแต่ดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส ProductInfoHeaderValue.
type: docs
weight: 105
url: /th/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) method


แปลงสตริงที่ส่งเข้ามาตั้งแต่ตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส [ProductInfoHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงเพื่อแยกวิเคราะห์. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์แล้วจะถูกกำหนด. |

### ค่าที่คืนกลับ

คืนความยาวของส่วนย่อยสตริงที่แยกวิเคราะห์, หากไม่เป็นเช่นนั้นคืนค่า 0.

## ดูเพิ่มเติม

* typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [ProductInfoHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)