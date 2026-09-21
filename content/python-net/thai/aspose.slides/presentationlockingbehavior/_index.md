---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumeration

แสดงพฤติกรรมที่เกี่ยวกับการจัดการแหล่งที่มาของ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) (ไฟล์หรือ **io.RawIOBase**) ขณะโหลดและทำงานกับอินสแตนซ์ของ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation).

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| :- | :- |
| LOAD_AND_RELEASE | แหล่งที่มาจะถูกล็อกเฉพาะในช่วงเวลาการดำเนินการของคอนสตรัคเตอร์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation).<br/>หาก [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/th/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) ถูกตั้งค่าเป็น false, BLOB ทั้งหมด <br/>จะถูกโหลดเข้าสู่หน่วยความจำ. ในกรณีอื่น, วิธีอื่นเช่นไฟล์ชั่วคราวอาจถูกใช้. พฤติกรรมนี้ช้ากว่า [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/th/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), และหากเป็นไปได้ที่จะส่งมอบความเป็นเจ้าของของแหล่งที่ม่าให้กับ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation), แนะนำให้ใช้ [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/th/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | แหล่งที่มาจะถูกล็อกตลอดอายุการใช้งานของอินสแตนซ์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) จนกว่าจะ <br/>ถูกกำจัด.<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/th/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) ต้องถูกตั้งค่าเป็น true เพื่อใช้พฤติกรรมนี้, มิฉะนั้นจะเกิดข้อยกเว้น.<br/>พฤติกรรมนี้แนะนำ, เนื่องจากเร็วกว่าและใช้หน่วยความจำน้อยกว่า [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/th/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### หมายเหตุ

แหล่งที่มาคือพารามิเตอร์ที่ส่งให้กับคอนสตรัคเตอร์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). ในตัวอย่างด้านล่าง, แหล่งที่มาคือไฟล์ "pres.pptx":

สำหรับตัวอย่างนี้, แหล่งที่มา ("pres.pptx" file) จะถูกล็อกสำหรับอายุการใช้งานของอินสแตนซ์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) , นั่นหมายความว่าไม่สามารถเปลี่ยนหรือทำลายโดยกระบวนการอื่นได้.


### ดูเพิ่มเติม
* คลาส [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)