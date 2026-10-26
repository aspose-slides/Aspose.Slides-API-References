---
title: ILegend
second_title: مرجع API Aspose.Slides for Java
description: يمثل خصائص وسيلة إيضاح المخططات.
type: docs
url: /ar/com.aspose.slides/ilegend/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

يمثل خصائص وسيلة إيضاح المخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOverlay()](#getOverlay--) | يحدد ما إذا كان سيسمح لعناصر المخطط الأخرى بتغطية وسيلة الإيضاح. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | يحدد ما إذا كان سيسمح لعناصر المخطط الأخرى بتغطية وسيلة الإيضاح. |
| [getPosition()](#getPosition--) | يحدد موضع وسيلة الإيضاح على المخطط. |
| [setPosition(int value)](#setPosition-int-) | يحدد موضع وسيلة الإيضاح على المخطط. |
| [getFormat()](#getFormat--) | يُرجع تنسيق وسيلة الإيضاح. |
| [getEntries()](#getEntries--) | يحصل على مدخلات وسيلة الإيضاح. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

يحدد ما إذا كان سيسمح لعناصر المخطط الأخرى بتغطية وسيلة الإيضاح. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

يحدد ما إذا كان سيسمح لعناصر المخطط الأخرى بتغطية وسيلة الإيضاح. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

يحدد موضع وسيلة الإيضاح على المخطط. القيم غير NaN للخصائص X, Y, Width, Heigt تتجاوز تأثير هذه الخاصية. قراءة/كتابة [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**الإرجاع:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

يحدد موضع وسيلة الإيضاح على المخطط. القيم غير NaN للخصائص X, Y, Width, Heigt تتجاوز تأثير هذه الخاصية. قراءة/كتابة [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يُرجع تنسيق وسيلة الإيضاح. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

يحصل على مدخلات وسيلة الإيضاح. قراءة فقط [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**الإرجاع:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)