---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: เป็นตัวจัดการการบันทึกภาพ SVG ในรูปแบบ markdown ของเหตุการณ์ SvgImageSavingDelegate.SvgImageSavingDelegate
type: docs
url: /th/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

เป็นตัวจัดการการบันทึกภาพ SVG ในรูปแบบ markdown ของเหตุการณ์ \#SvgImageSavingDelegate.SvgImageSavingDelegate
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | เรียกใช้สำหรับแต่ละภาพ SVG ระหว่างการส่งออกเป็น Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

เรียกใช้สำหรับแต่ละภาพ SVG ระหว่างการส่งออกเป็น Markdown. คืนค่า true เพื่อใช้ลิงก์ที่ระบุ, หรือ false เพื่อใช้ตรรกะการบันทึกค่าเริ่มต้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | ภาพ SVG ที่กำลังส่งออก. |
| link | java.lang.String[] | ลิงก์ Markdown ที่ใช้เมื่อคืนค่า true. |

**ผลลัพธ์:**
boolean