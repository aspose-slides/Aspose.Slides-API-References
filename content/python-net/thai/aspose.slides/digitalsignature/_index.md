---
title: DigitalSignature class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/digitalsignature/
---
## DigitalSignature คลาส

ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม

The DigitalSignature type exposes the following members:

## ตัวสร้าง

| Constructor | Description |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/th/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | สร้างอ็อบเจ็กต์ DigitalSignature ใหม่โดยใช้ใบรับรองที่ระบุ |
| [`__init__(self, file_path, password)`](/slides/python-net/th/aspose.slides/digitalsignature/__init__/#str-str) | สร้างอ็อบเจ็กต์ DigitalSignature ใหม่โดยใช้เส้นทางไฟล์ใบรับรองและรหัสผ่านที่ระบุ |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`certificate`](/slides/python-net/th/aspose.slides/digitalsignature/certificate/) | อ็อบเจ็กต์ Certificate ที่ใช้ในการลงนามเอกสาร.<br/>            อ่านอย่างเดียว **System.Security.Cryptography.X509Certificates.X509Certificate2** |
| [`is_valid`](/slides/python-net/th/aspose.slides/digitalsignature/is_valid/) | หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่ได้ถูกดัดแปลงค่า นี้จะเป็น true.<br/>            อ่านอย่างเดียว **bool** |
| [`sign_time`](/slides/python-net/th/aspose.slides/digitalsignature/sign_time/) | เวลาที่เอกสารถูกลงนาม.<br/>            อ่านอย่างเดียว **System.DateTime** |
| [`comments`](/slides/python-net/th/aspose.slides/digitalsignature/comments/) | วัตถุประสงค์ของลายเซ็น.<br/>            อ่าน/เขียน **str** |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)