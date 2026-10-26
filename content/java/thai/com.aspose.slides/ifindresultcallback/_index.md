---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: อินเตอร์เฟซ Callback ที่ใช้สำหรับรับผลลัพธ์การค้นหาข้อความ.
type: docs
url: /th/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

อินเตอร์เฟซ Callback ที่ใช้สำหรับรับผลลัพธ์การค้นหาข้อความ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | เมธอด Callback ที่รับข้อมูลเกี่ยวกับข้อความที่พบ |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


เมธอด Callback ที่รับข้อมูลเกี่ยวกับข้อความที่พบ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) ที่ข้อความถูกพบ |
| sourceText | java.lang.String | ข้อความต้นฉบับที่ข้อความถูกพบ |
| foundText | java.lang.String | ข้อความที่พบ |
| textPosition | int | ตำแหน่งของข้อความที่พบ |