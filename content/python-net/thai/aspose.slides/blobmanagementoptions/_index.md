---
title: BlobManagementOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions คลาส

เป็นตัวแทนของตัวเลือกที่สามารถใช้จัดการกฎการจัดการ BLOB และการตั้งค่า BLOB อื่น ๆ

ประเภท BlobManagementOptions เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides/blobmanagementoptions/__init__/#) | สร้างตัวเลือกการจัดการ blob เริ่มต้นใหม่ |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/th/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของของแหล่งข้อมูล - ไฟล์ <br/>            หรือสตรีม ในช่วงอายุของตัวอย่างได้หรือไม่ หากตัวอย่างเป็นเจ้าของ มันจะล็อกแหล่งข้อมูล สิ่งนี้ช่วย <br/>            ลดการใช้หน่วยความจำและเพิ่มประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งข้อมูล (สตรีมหรือไฟล์) <br/>            ไม่สามารถเปลี่ยนแปลงได้ในช่วงอายุของตัวอย่าง Presentation |
| [`is_temporary_files_allowed`](/slides/python-net/th/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | คุณสมบัตินี้กำหนดว่ามีการสร้างไฟล์ชั่วคราวระหว่างทำงานกับ BLOBs หรือไม่ ซึ่งจะทำให้ <br/>            ลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์<br/>            ไฟล์ทั้งหมดจะถูกลบหลังจากการทำงานกับการนำเสนอเสร็จสิ้น |
| [`temp_files_root_path`](/slides/python-net/th/aspose.slides/blobmanagementoptions/temp_files_root_path/) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง ระบบไดเรกทอรีชั่วคราวจะถูกใช้เป็นค่าเริ่มต้น <br/>            กระบวนการโฮสต์ควรมีสิทธิ์ในการ <br/>            สร้างไฟล์และโฟลเดอร์ที่นั่น |
| [`max_blobs_bytes_in_memory`](/slides/python-net/th/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | กำหนดขนาดรวมสูงสุด (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOB ทั้งหมด<br/>            จะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว) <br/>            การเก็บ BLOB ในหน่วยความจำเพิ่มประสิทธิภาพสูงสุดแต่สามารถทำให้ใช้หน่วยความจำมากได้ ใช้<br/>            คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)