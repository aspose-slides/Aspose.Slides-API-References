---
title: ISmartArt
second_title: مرجع API لـ Aspose.Slides للغة Java
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
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | إرجاع مجموعة من جميع العقد في كائن SmartArt. |
| [getNodes()](#getNodes--) | إرجاع مجموعة من العقد الجذرية في كائن SmartArt. |
| [getLayout()](#getLayout--) | إرجاع أو ضبط تخطيط كائن SmartArt. |
| [setLayout(int value)](#setLayout-int-) | إرجاع أو ضبط تخطيط كائن SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | إرجاع أو ضبط النمط السريع لكائن SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | إرجاع أو ضبط النمط السريع لكائن SmartArt. |
| [getColorStyle()](#getColorStyle--) | إرجاع أو ضبط نمط اللون لكائن SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | إرجاع أو ضبط نمط اللون لكائن SmartArt. |
| [isReversed()](#isReversed--) | إرجاع أو ضبط حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. |
| [setReversed(boolean value)](#setReversed-boolean-) | إرجاع أو ضبط حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

إرجاع مجموعة من جميع العقد في كائن SmartArt. للقراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**الإرجاع:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

إرجاع مجموعة من العقد الجذرية في كائن SmartArt. للقراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**الإرجاع:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

إرجاع أو ضبط تخطيط كائن SmartArt. قراءة/كتابة [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**الإرجاع:**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

إرجاع أو ضبط تخطيط كائن SmartArt. قراءة/كتابة [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

إرجاع أو ضبط النمط السريع لكائن SmartArt. قراءة/كتابة [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**الإرجاع:**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

إرجاع أو ضبط النمط السريع لكائن SmartArt. قراءة/كتابة [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

إرجاع أو ضبط نمط اللون لكائن SmartArt. قراءة/كتابة [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**الإرجاع:**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

إرجاع أو ضبط نمط اللون لكائن SmartArt. قراءة/كتابة [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

إرجاع أو ضبط حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

إرجاع أو ضبط حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |