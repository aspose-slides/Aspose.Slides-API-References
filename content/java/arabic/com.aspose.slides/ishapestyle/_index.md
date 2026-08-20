---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Represent shapes style reference.
type: docs
url: /ar/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

تمثيل مرجع نمط الشكل.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getLineColor()](#getLineColor--) | يعيد لون حدود الشكل. |
| [getLineStyleIndex()](#getLineStyleIndex--) | يعيد أو يحدد فهرس عمود الخط في مصفوفة النمط. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | يعيد أو يحدد فهرس عمود الخط في مصفوفة النمط. |
| [getFillColor()](#getFillColor--) | يعيد لون تعبئة الشكل. |
| [getFillStyleIndex()](#getFillStyleIndex--) | يعيد أو يحدد فهرس عمود تعبئة الشكل في مصفوفات النمط. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | يعيد أو يحدد فهرس عمود تعبئة الشكل في مصفوفات النمط. |
| [getEffectColor()](#getEffectColor--) | يعيد لون تأثير الشكل. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | يعيد أو يحدد فهرس عمود تأثير الشكل في مصفوفة النمط. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | يعيد أو يحدد فهرس عمود تأثير الشكل في مصفوفة النمط. |
| [getFontColor()](#getFontColor--) | يعيد لون خط الشكل. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | يعيد أو يحدد فهرس الخط الخاص بالشكل في مجموعة الخطوط. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | يعيد أو يحدد فهرس الخط الخاص بالشكل في مجموعة الخطوط. |

### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

يعيد لون حدود الشكل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

يعيد أو يحدد فهرس عمود الخط في مصفوفة النمط. قابل للقراءة والكتابة int.

**الإرجاع:**
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

يعيد أو يحدد فهرس عمود الخط في مصفوفة النمط. قابل للقراءة والكتابة int.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

يعيد لون تعبئة الشكل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

يعيد أو يحدد فهرس عمود تعبئة الشكل في مصفوفات النمط. 0 يعني عدم وجود تعبئة، القيمة الموجبة - فهرس في أنماط تعبئة السمة، القيمة السالبة - فهرس في أنماط خلفية السمة. قابل للقراءة والكتابة short.

**الإرجاع:**
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

يعيد أو يحدد فهرس عمود تعبئة الشكل في مصفوفات النمط. 0 يعني عدم وجود تعبئة، القيمة الموجبة - فهرس في أنماط تعبئة السمة، القيمة السالبة - فهرس في أنماط خلفية السمة. قابل للقراءة والكتابة short.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

يعيد لون تأثير الشكل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

يعيد أو يحدد فهرس عمود تأثير الشكل في مصفوفة النمط. قابل للقراءة والكتابة long.

**الإرجاع:**
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

يعيد أو يحدد فهرس عمود تأثير الشكل في مصفوفة النمط. قابل للقراءة والكتابة long.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

يعيد لون خط الشكل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

يعيد أو يحدد فهرس الخط الخاص بالشكل في مجموعة الخطوط. قابل للقراءة والكتابة [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**الإرجاع:**
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

يعيد أو يحدد فهرس الخط الخاص بالشكل في مجموعة الخطوط. قابل للقراءة والكتابة [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |