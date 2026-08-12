---
title: VerifyData()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบลายเซ็นของข้อมูล.
type: docs
weight: 209
url: /th/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) วิธีการ

ตรวจสอบลายเซ็นของข้อมูล.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) to check signature for. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash algorithm to use. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature as received. |

### ค่าที่ส่งคืน

True หากลายเซ็นถูกต้อง, false ในกรณีอื่น.

## ดูเพิ่มเติม

* กำหนดประเภท [ByteArrayPtr](../../../system/bytearrayptr/)
* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [RSACryptoServiceProvider](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)