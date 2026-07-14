---
title: IChartTitle
second_title: Aspose.Slides للأندرويد عبر مرجع API لجافا
description: يمثل خصائص عنوان المخطط.
type: docs
url: /ar/com.aspose.slides/icharttitle/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

يمثل خصائص عنوان المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOverlay()](#getOverlay--) | يحدد ما إذا كان يجب السماح لعناصر المخطط الأخرى بتغطية العنوان. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | يحدد ما إذا كان يجب السماح لعناصر المخطط الأخرى بتغطية العنوان. |
| [getFormat()](#getFormat--) | يعيد أنماط التعبئة، الخط، والتأثير لعنوان. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

يحدد ما إذا كان يجب السماح لعناصر المخطط الأخرى بتغطية العنوان. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

يحدد ما إذا كان يجب السماح لعناصر المخطط الأخرى بتغطية العنوان. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يعيد أنماط التعبئة، الخط، والتأثير لعنوان. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)