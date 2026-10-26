---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: เป็นตัวแทนของตัวจัดการการบันทึกภาพ SVG ในรูปแบบ markdown ของเหตุการณ์ SvgImageSavingDelegate.SvgImageSavingDelegate
type: docs
url: /th/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

เป็นตัวแทนของตัวจัดการการบันทึกภาพ SVG ในรูปแบบ markdown ของ \#SvgImageSavingDelegate.SvgImageSavingDelegate event.
## วิธีการ

| Method | Description |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | ถูกเรียกใช้สำหรับแต่ละภาพ SVG ระหว่างการส่งออกเป็น Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```


ถูกเรียกใช้สำหรับแต่ละภาพ SVG ระหว่างการส่งออกเป็น Markdown. คืนค่า true เพื่อใช้ลิงก์ที่ระบุ, หรือ false เพื่อใช้ตรรกะการบันทึกค่าเริ่มต้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | ภาพ SVG ที่กำลังส่งออก. |
| link | java.lang.String[] | ลิงก์ Markdown ที่จะใช้เมื่อตอบกลับเป็น true. |

**ผลลัพธ์:**
boolean