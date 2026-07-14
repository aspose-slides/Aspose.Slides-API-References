---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงตัวจัดการการบันทึกรูปภาพ markdown ของเหตุการณ์ ImageSavingDelegate.ImageSavingDelegate
type: docs
url: /th/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

แสดงตัวจัดการการบันทึกรูปภาพ markdown ของเหตุการณ์ #ImageSavingDelegate.ImageSavingDelegate event.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invoked for each non-SVG image (bitmap or metafile) during Markdown export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

จะถูกเรียกสำหรับแต่ละรูปภาพที่ไม่ใช่ SVG (bitmap หรือ metafile) ในระหว่างการส่งออก Markdown. คืนค่า true เพื่อใช้ลิงค์ที่ระบุ, หรือ false เพื่อใช้ตรรกะการบันทึกค่าเริ่มต้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | รูปภาพที่กำลังส่งออก (bitmap หรือ metafile). |
| format | int | รูปแบบของรูปภาพ. |
| link | java.lang.String[] | ลิงค์ Markdown ที่ใช้เมื่อคืนค่าเป็น true. |

**ผลลัพธ์:**
boolean