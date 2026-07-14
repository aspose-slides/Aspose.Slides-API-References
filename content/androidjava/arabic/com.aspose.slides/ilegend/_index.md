---
title: ILegend
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
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
| [getOverlay()](#getOverlay--) | يحدد ما إذا كان يجب السماح لعناصر المخطط الأخرى بتغطية وسيلة الإيضاح. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | يحدد ما إذا كان يجب السماح لعناصر المخطط الأخرى بتغطية وسيلة الإيضاح. |
| [getPosition()](#getPosition--) | يحدد موضع وسيلة الإيضاح على المخطط. |
| [setPosition(int value)](#setPosition-int-) | يحدد موضع وسيلة الإيضاح على المخطط. |
| [getFormat()](#getFormat--) | يرجع تنسيق وسيلة الإيضاح. |
| [getEntries()](#getEntries--) | يحصل على مدخلات وسيلة الإيضاح. |

### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

يحدد ما إذا كان يجب السماح لعناصر المخطط الأخرى بتغطية وسيلة الإيضاح. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

يحدد ما إذا كان يجب السماح لعناصر المخطط الأخرى بتغطية وسيلة الإيضاح. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

يحدد موضع وسيلة الإيضاح على المخطط. القيم غير NaN للخصائص X و Y و Width و Heigt تتجاوز تأثير هذه الخاصية. قراءة/كتابة [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**القيمة المرجعة:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

يحدد موضع وسيلة الإيضاح على المخطط. القيم غير NaN للخصائص X و Y و Width و Heigt تتجاوز تأثير هذه الخاصية. قراءة/كتابة [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يرجع تنسيق وسيلة الإيضاح. للقراءة فقط [IFormat](../../com.aspose.slides/iformat).

**القيمة المرجعة:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

يحصل على مدخلات وسيلة الإيضاح. للقراءة فقط [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**القيمة المرجعة:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)