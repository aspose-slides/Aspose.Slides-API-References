---
title: Merger
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของกลุ่มเมธอดสำหรับการรวมงานนำเสนอ PowerPoint ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว
type: docs
url: /th/com.aspose.slides/merger/
---
**การสืบทอด:**
java.lang.Object
```
public class Merger
```

เป็นกลุ่มของเมธอดสำหรับการรวมงานนำเสนอ PowerPoint ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | รวมงานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | รวมงานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | รวมงานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | รวมงานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

รวมงานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | อาร์เรย์ของชื่อไฟล์งานนำเสนอที่เป็นอินพุต |
| outputFileName | java.lang.String | ชื่อไฟล์ผลลัพธ์ของไฟล์งานนำเสนอที่ถูกรวม |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

รวมงานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | อาร์เรย์ของชื่อไฟล์งานนำเสนอที่เป็นอินพุต |
| outputFileName | java.lang.String | ชื่อไฟล์ผลลัพธ์ของไฟล์งานนำเสนอที่ถูกรวม |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกเพิ่มเติมที่กำหนดวิธีการบันทึกงานนำเสนอที่ถูกรวม |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

รวมงานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | อาร์เรย์ของชื่อไฟล์งานนำเสนอที่เป็นอินพุต |
| outputStream | java.io.OutputStream | สตรีมผลลัพธ์ |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

รวมงานนำเสนอ PowerPoint หลายไฟล์ที่มีรูปแบบเดียวกันเป็นไฟล์เดียว

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | อาร์เรย์ของชื่อไฟล์งานนำเสนอที่เป็นอินพุต |
| outputStream | java.io.OutputStream | สตรีมผลลัพธ์ |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | ตัวเลือกเพิ่มเติมที่กำหนดวิธีการบันทึกงานนำเสนอที่ถูกรวม |