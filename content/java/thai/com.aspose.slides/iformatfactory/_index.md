---
title: IFormatFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้างรูปแบบผ่านอินเทอร์เฟซ COM.
type: docs
url: /th/com.aspose.slides/iformatfactory/
---```
public interface IFormatFactory
```

อนุญาตให้สร้างรูปแบบผ่านอินเทอร์เฟซ COM.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createPortionFormat()](#createPortionFormat--) | สร้างใหม่ [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | สร้างใหม่ [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | สร้างใหม่ [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### createPortionFormat() {#createPortionFormat--}
```
public abstract IPortionFormat createPortionFormat()
```

สร้างใหม่ [IPortionFormat](../../com.aspose.slides/iportionformat).

**ส่งกลับ:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - รูปแบบส่วนใหม่.
### createParagraphFormat() {#createParagraphFormat--}
```
public abstract IParagraphFormat createParagraphFormat()
```

สร้างใหม่ [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**ส่งกลับ:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - รูปแบบย่อหน้าใหม่.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public abstract ITextFrameFormat createTextFrameFormat()
```

สร้างใหม่ [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**ส่งกลับ:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - รูปแบบกรอบข้อความใหม่.