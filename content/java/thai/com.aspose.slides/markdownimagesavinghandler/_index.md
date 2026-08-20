---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: แสดงถึงตัวจัดการการบันทึกภาพ markdown ของเหตุการณ์ ImageSavingDelegate.ImageSavingDelegate
type: docs
url: /th/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

แสดงถึงตัวจัดการการบันทึกภาพ markdown ของเหตุการณ์ \#ImageSavingDelegate.ImageSavingDelegate event.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | ถูกเรียกสำหรับแต่ละภาพที่ไม่ใช่ SVG (bitmap หรือ metafile) ระหว่างการส่งออก Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

ถูกเรียกสำหรับแต่ละภาพที่ไม่ใช่ SVG (bitmap หรือ metafile) ระหว่างการส่งออก Markdown. คืนค่า true เพื่อใช้ลิงก์ที่ระบุ, หรือ false เพื่อใช้ตรรกะการบันทึกเริ่มต้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | ภาพที่กำลังส่งออก (bitmap หรือ metafile). |
| format | int | รูปแบบของภาพ. |
| link | java.lang.String[] | ลิงก์ Markdown ที่จะใช้เมื่อคืนค่า true. |

**คืนค่า:**
boolean