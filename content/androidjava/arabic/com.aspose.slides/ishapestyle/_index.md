---
title: IShapeStyle
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: تمثيل مرجع نمط الشكل.
type: docs
url: /ar/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

تمثيل مرجع نمط الشكل.
## الطرق

| Method | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | يعيد لون حدود الشكل. |
| [getLineStyleIndex()](#getLineStyleIndex--) | يعيد أو يضبط فهرس العمود للخط في مصفوفة النمط. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | يعيد أو يضبط فهرس العمود للخط في مصفوفة النمط. |
| [getFillColor()](#getFillColor--) | يعيد لون تعبئة الشكل. |
| [getFillStyleIndex()](#getFillStyleIndex--) | يعيد أو يضبط فهرس عمود تعبئة الشكل في مصفوفات النمط. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | يعيد أو يضبط فهرس عمود تعبئة الشكل في مصفوفات النمط. |
| [getEffectColor()](#getEffectColor--) | يعيد لون تأثير الشكل. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | يعيد أو يضبط فهرس عمود تأثير الشكل في مصفوفة النمط. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | يعيد أو يضبط فهرس عمود تأثير الشكل في مصفوفة النمط. |
| [getFontColor()](#getFontColor--) | يعيد لون خط الشكل. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | يعيد أو يضبط فهرس خط الشكل في مجموعة الخطوط. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | يعيد أو يضبط فهرس خط الشكل في مجموعة الخطوط. |

### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

يعيد لون حدود الشكل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

يعيد أو يضبط فهرس عمود الخط في مصفوفة النمط. قراءة/كتابة int.

**القيمة المرجعة:**
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

يعيد أو يضبط فهرس عمود الخط في مصفوفة النمط. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

يعيد لون تعبئة الشكل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

يعيد أو يضبط فهرس عمود تعبئة الشكل في مصفوفات النمط. 0 يعني بدون تعبئة، القيمة الموجبة - الفهرس في أنماط تعبئة السمة، القيمة السالبة - الفهرس في أنماط خلفية السمة. قراءة/كتابة short.

**القيمة المرجعة:**
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

يعيد أو يضبط فهرس عمود تعبئة الشكل في مصفوفات النمط. 0 يعني بدون تعبئة، القيمة الموجبة - الفهرس في أنماط تعبئة السمة، القيمة السالبة - الفهرس في أنماط خلفية السمة. قراءة/كتابة short.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

يعيد لون تأثير الشكل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

يعيد أو يضبط فهرس عمود تأثير الشكل في مصفوفة النمط. قراءة/كتابة long.

**القيمة المرجعة:**
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

يعيد أو يضبط فهرس عمود تأثير الشكل في مصفوفة النمط. قراءة/كتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

يعيد لون خط الشكل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

يعيد أو يضبط فهرس خط الشكل في مجموعة الخطوط. قراءة/كتابة [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**القيمة المرجعة:**
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

يعيد أو يضبط فهرس خط الشكل في مجموعة الخطوط. قراءة/كتابة [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |