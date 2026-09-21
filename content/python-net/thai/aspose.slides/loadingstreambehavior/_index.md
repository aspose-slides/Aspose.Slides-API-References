---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enumeration

**io.RawIOBase** ที่ส่งเข้าเมธอดจะถูกถือว่าเป็น Binary Large Object (BLOB) (ดูคำอธิบายของ [`IBlobManagementOptions`](/slides/python-net/th/aspose.slides/iblobmanagementoptions)) ค่าของ enumeration นี้ระบุวิธีที่ **io.RawIOBase** ควรได้รับการจัดการเมื่อถูกส่งเข้าเมธอด ขึ้นอยู่กับความต้องการ สามารถตัดสินใจต่าง ๆ เพื่อให้ได้พฤติกรรมที่มีประสิทธิภาพสูงสุด

LoadingStreamBehavior มีสมาชิกต่อไปนี้:

## ฟิลด์

| Field | Description |
| :- | :- |
| READ_STREAM_AND_RELEASE | สตรีมจะถูกอ่านจนถึงจุดสิ้นสุดและจากนั้นจะถูกปล่อยออก - คือ จะรับประกันว่า สตรีมนี้ <br/>            จะไม่ถูกใช้โดยอินสแตนซ์ของ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) ในอนาคต สามารถปิดโดยโค้ดของลูกค้า <br/>            หรือใช้ในวิธีอื่นใดก็ได้. |
| KEEP_LOCKED | สตรีมจะถูกล็อกภายในอ็อบเจ็กต์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) คือ ความเป็นเจ้าของของ <br/>            สตรีมจะถูกโอนย้าย อ็อบเจ็กต์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) จะรับผิดชอบในการ <br/>            ปิดการใช้งานสตรีมอย่างถูกต้องเมื่ออ็อบเจ็กต์นี้ถูกปิดการใช้งานเอง <br/>            พฤติกรรมนี้มีประโยชน์อย่างมากเมื่อคุณต้องการทำการซีเรียลไลซ์ไฟล์ BLOB ขนาดใหญ่ (เช่น วิดีโอหรือเสียงขนาดใหญ่ - ดูคำอธิบายของ [`IBlobManagementOptions`](/slides/python-net/th/aspose.slides/iblobmanagementoptions)) และต้องการป้องกันการโหลด <br/>            ไฟล์นี้เข้าสู่หน่วยความจำหรือปัญหาประสิทธิภาพอื่น ๆ คุณสามารถเปิด **System.IO.FileStream** <br/>            สำหรับไฟล์นี้และส่งต่อให้เมธอดโดยเลือก LoadingStreamBehavior ของ [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/th/aspose.slides/loadingstreambehavior/KEEP_LOCKED). |

### ดูเพิ่มเติม
* คลาส [`IBlobManagementOptions`](/slides/python-net/th/aspose.slides/iblobmanagementoptions)
* คลาส [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)