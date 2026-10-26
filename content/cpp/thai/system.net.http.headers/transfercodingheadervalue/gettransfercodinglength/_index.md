---
title: GetTransferCodingLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุให้เป็นอินสแตนซ์ของคลาส TransferCodingHeaderValue.
type: docs
weight: 105
url: /th/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุให้เป็นอินสแตนซ์ของคลาส [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่จะพาร์ส |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการพาร์ส |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | อินสแตนซ์ที่วัตถุที่พาร์สแล้วจะถูกกำหนด |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | ตัวแทนที่ใช้ในการสร้างอินสแตนซ์ของคลาส [TransferCodingHeaderValue](../) |

### ค่าที่ส่งคืน

คืนความยาวของสตริงย่อยที่พาร์สแล้ว, มิฉะนั้นจะเป็น 0.

## ดูเพิ่มเติม

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [TransferCodingHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)