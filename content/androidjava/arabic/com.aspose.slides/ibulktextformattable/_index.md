---
title: IBulkTextFormattable
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل كائنًا يتيح إمكانية تعيين تنسيقات عناصر النص الفرعية بشكل جماعي.
type: docs
url: /ar/com.aspose.slides/ibulktextformattable/
---```
public interface IBulkTextFormattable
```

يمثّل كائنًا يتيح إمكانية تعيين تنسيقات عناصر النص الفرعية بشكل جماعي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | يضبط خصائص تنسيق الجزء المحدد لجميع أجزاء العنصر. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات العنصر. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات النص الخاصة بالعنصر. |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setTextFormat(IPortionFormat source)
```

يضبط خصائص تنسيق الجزء المحدد لجميع أجزاء العنصر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | كائن IPortionFormat مع الخصائص اللازمة مُضَبَطة. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public abstract void setTextFormat(IParagraphFormat source)
```

يضبط خصائص تنسيق الفقرة المحددة لجميع فقرات العنصر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | كائن IParagraphFormat مع الخصائص اللازمة مُضَبَطة. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public abstract void setTextFormat(ITextFrameFormat source)
```

يضبط خصائص تنسيق إطار النص المحددة لجميع إطارات النص الخاصة بالعنصر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | كائن ITextFrameFormat مع الخصائص اللازمة مُضَبَطة. |