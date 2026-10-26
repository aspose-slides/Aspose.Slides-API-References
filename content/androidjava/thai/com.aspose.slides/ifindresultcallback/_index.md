---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /th/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

อินเทอร์เฟซ Callback ที่ใช้สำหรับรับผลลัพธ์การค้นหาข้อความ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | เมธอด Callback ที่รับข้อมูลเกี่ยวกับข้อความที่พบ |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

เมธอด Callback ที่รับข้อมูลเกี่ยวกับข้อความที่พบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) ที่ข้อความถูกพบ |
| sourceText | java.lang.String | ข้อความต้นทางที่ข้อความถูกพบ |
| foundText | java.lang.String | ข้อความที่พบ |
| textPosition | int | ตำแหน่งของข้อความที่พบ |