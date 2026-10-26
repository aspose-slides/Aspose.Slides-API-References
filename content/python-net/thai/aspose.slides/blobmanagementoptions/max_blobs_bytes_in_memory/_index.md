---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory คุณสมบัติ
กำหนดขนาดสูงสุดรวม (หน่วยไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOB ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จึงใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว) เท่านั้น การเก็บ BLOB ในหน่วยความจำช่วยเพิ่มประสิทธิภาพสูงสุดแต่อาจทำให้การใช้หน่วยความจำสูง ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ.

### หมายเหตุ

คุณสมบัตินี้จะถูกละเว้นหาก [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/th/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นที่จัดเก็บเดียวที่มีอยู่และการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

### คำจำกัดความ:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`BlobManagementOptions`](/slides/python-net/th/aspose.slides/blobmanagementoptions)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)