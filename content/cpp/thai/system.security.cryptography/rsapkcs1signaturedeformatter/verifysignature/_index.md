---
title: VerifySignature()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตรวจสอบลายเซ็นของแฮชข้อมูล.
type: docs
weight: 40
url: /th/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

ตรวจสอบลายเซ็นของค่าแฮชข้อมูล

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | แฮชที่คำนวนจากข้อมูล |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ลายเซ็นที่ได้รับสำหรับข้อมูล |

### ค่าที่คืนกลับ

True หากลายเซ็นถูกต้อง, false หากไม่เป็นเช่นนั้น.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [RSAPKCS1SignatureDeformatter](../)
* เนมสเปส [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)