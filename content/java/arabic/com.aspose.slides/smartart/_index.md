---
title: SmartArt
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مخطط SmartArt
type: docs
url: /ar/com.aspose.slides/smartart/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

يمثل مخطط SmartArt
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | يرجع مجموعات جميع العقد في كائن SmartArt. |
| [getNodes()](#getNodes--) | يرجع مجموعات العقد الجذرية في كائن SmartArt. |
| [getLayout()](#getLayout--) | يرجع أو يعيّن تخطيط كائن SmartArt. |
| [setLayout(int value)](#setLayout-int-) | يرجع أو يعيّن تخطيط كائن SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | يرجع أو يعيّن النمط السريع لكائن SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | يرجع أو يعيّن النمط السريع لكائن SmartArt. |
| [getColorStyle()](#getColorStyle--) | يرجع أو يعيّن نمط اللون لكائن SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | يرجع أو يعيّن نمط اللون لكائن SmartArt. |
| [isReversed()](#isReversed--) | إرجاع أو تعيين حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. |
| [setReversed(boolean value)](#setReversed-boolean-) | إرجاع أو تعيين حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. |
### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```


يرجع مجموعات جميع العقد في كائن SmartArt. للقراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**القيمة المرجعة:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```


يرجع مجموعات العقد الجذرية في كائن SmartArt. للقراءة فقط [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**القيمة المرجعة:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```


يرجع أو يعيّن تخطيط كائن SmartArt. قراءة/كتابة [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**القيمة المرجعة:**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```


يرجع أو يعيّن تخطيط كائن SmartArt. قراءة/كتابة [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```


يرجع أو يعيّن النمط السريع لكائن SmartArt. قراءة/كتابة [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**القيمة المرجعة:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```


يرجع أو يعيّن النمط السريع لكائن SmartArt. قراءة/كتابة [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```


يرجع أو يعيّن نمط اللون لكائن SmartArt. قراءة/كتابة [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**القيمة المرجعة:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```


يرجع أو يعيّن نمط اللون لكائن SmartArt. قراءة/كتابة [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```


إرجاع أو تعيين حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. قراءة/كتابة boolean .

**القيمة المرجعة:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```


إرجاع أو تعيين حالة مخطط SmartArt بالنسبة إلى (من اليسار إلى اليمين) LTR أو (من اليمين إلى اليسار) RTL، إذا كان المخطط يدعم العكس. قراءة/كتابة boolean .

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |