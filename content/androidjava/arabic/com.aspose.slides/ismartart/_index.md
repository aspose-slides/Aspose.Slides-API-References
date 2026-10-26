---
title: ISmartArt
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل مخطط SmartArt.
type: docs
url: /ar/com.aspose.slides/ismartart/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

يمثل مخطط SmartArt.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | إرجاع مجموعات جميع العقد في كائن SmartArt. |
| [getNodes()](#getNodes--) | إرجاع مجموعات العقد الجذرية في كائن SmartArt. |
| [getLayout()](#getLayout--) | إرجاع أو تعيين layout لكائن SmartArt. |
| [setLayout(int value)](#setLayout-int-) | إرجاع أو تعيين layout لكائن SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | إرجاع أو تعيين quick style لكائن SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | إرجاع أو تعيين quick style لكائن SmartArt. |
| [getColorStyle()](#getColorStyle--) | إرجاع أو تعيين color style لكائن SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | إرجاع أو تعيين color style لكائن SmartArt. |
| [isReversed()](#isReversed--) | إرجاع أو تعيين حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. |
| [setReversed(boolean value)](#setReversed-boolean-) | إرجاع أو تعيين حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

إرجاع مجموعات جميع العقد في كائن SmartArt. قراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**القيمة المرجعة:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

إرجاع مجموعات العقد الجذرية في كائن SmartArt. قراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**القيمة المرجعة:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

إرجاع أو تعيين layout لكائن SmartArt. قراءة/كتابة [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**القيمة المرجعة:**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

إرجاع أو تعيين layout لكائن SmartArt. قراءة/كتابة [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

إرجاع أو تعيين quick style لكائن SmartArt. قراءة/كتابة [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**القيمة المرجعة:**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

إرجاع أو تعيين quick style لكائن SmartArt. قراءة/كتابة [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

إرجاع أو تعيين color style لكائن SmartArt. قراءة/كتابة [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**القيمة المرجعة:**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

إرجاع أو تعيين color style لكائن SmartArt. قراءة/كتابة [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

إرجاع أو تعيين حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

إرجاع أو تعيين حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |