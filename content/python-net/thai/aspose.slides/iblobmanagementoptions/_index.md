---
title: IBlobManagementOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions คลาส

Binary Large Object (BLOB) คือข้อมูลไบนารีที่เก็บเป็นเอกเทศหนึ่งหน่วย - เช่น BLOB สามารถเป็นไฟล์เสียง, วิดีโอ หรือการนำเสนอเองได้ เทคนิคหลายอย่างถูกใช้เพื่อเพิ่มประสิทธิภาพการใช้หน่วยความจำขณะทำงานกับ BLOBs - ไม่ว่าจะเป็น BLOB ที่ได้ถูกเก็บไว้ในการนำเสนอแล้วหรือถูกเพิ่มภายหลังโดยโปรแกรม Using [`IBlobManagementOptions`](/slides/python-net/th/aspose.slides/iblobmanagementoptions) คุณสามารถเปลี่ยนแปลงพฤติกรรมที่แตกต่างเกี่ยวกับการจัดการ BLOBs สำหรับอายุการใช้งานของอินสแตนซ์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation).

The IBlobManagementOptions type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/th/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของของแหล่งที่มา - ไฟล์ <br/>            หรือสตรีมระหว่างอายุการใช้งานของตัวอย่างได้หรือไม่ หากตัวอย่างเป็นเจ้าของ จะทำการล็อกแหล่งที่มา สิ่งนี้ช่วย <br/>            ปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งที่มา (สตรีมหรือไฟล์) <br/>            จะไม่สามารถเปลี่ยนแปลงได้ระหว่างอายุการใช้งานของ Presentation นี้ ตัวอย่างเช่น: |
| [`is_temporary_files_allowed`](/slides/python-net/th/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | คุณสมบัตินี้กำหนดว่าจัดไฟล์ชั่วคราวได้หรือไม่ขณะทำงานกับ BLOBs ซึ่งทำให้การใช้หน่วยความจำลดลงอย่างมาก <br/>            แต่ต้องการสิทธิ์ในการสร้างไฟล์.<br/>            ไฟล์ทั้งหมดจะถูกลบหลังจากการทำงานกับการนำเสนอเส็จสิ้น. |
| [`temp_files_root_path`](/slides/python-net/th/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น ไดเรกทอรีชั่วคราวของระบบจะถูกใช้เป็นค่าเริ่มต้น <br/>            กระบวนการโฮสต์ควรมีสิทธิ์ในการ <br/>            สร้างไฟล์และโฟลเดอร์ในที่นั้น. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/th/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ ตามค่าเริ่มต้น BLOB ทั้งหมด<br/>            จะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จึงใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว)<br/>            การเก็บ BLOBs ในหน่วยความจำทำให้ประสิทธิภาพสูงสุดแต่ก็อาจทำให้การใช้หน่วยความจำสูง ใช้<br/>            คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ. |

### ดูเพิ่มเติม
* คลาส [`IBlobManagementOptions`](/slides/python-net/th/aspose.slides/iblobmanagementoptions)
* คลาส [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)