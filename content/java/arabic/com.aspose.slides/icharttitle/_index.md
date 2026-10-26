---
title: IChartTitle
second_title: Aspose.Slides لمرجع API Java
description: يمثل خصائص عنوان المخطط.
type: docs
url: /ar/com.aspose.slides/icharttitle/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

يمثل خصائص عنوان المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOverlay()](#getOverlay--) | يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بالتداخل مع العنوان. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بالتداخل مع العنوان. |
| [getFormat()](#getFormat--) | يعيد نمط التعبئة والخط وال تأثير لعنوان. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بالتداخل مع العنوان. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

يحدد ما إذا كان يُسمح لعناصر المخطط الأخرى بالتداخل مع العنوان. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يعيد نمط التعبئة والخط وال تأثير لعنوان. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

**القيمة المرجعة:**
[IFormat](../../com.aspose.slides/iformat)