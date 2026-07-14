---
title: Tab
second_title: Aspose.Slides لنظام Android عبر واجهة برمجة تطبيقات Java
description: يمثل تبويبًا للنص.
type: docs
url: /ar/com.aspose.slides/tab/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ITab](../../com.aspose.slides/itab)  
```
public final class Tab extends PVIObject implements ITab
```

يمثل تبويبًا للنص.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Creates new Tab |
## الدوال

| الدالة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Returns or sets position of a tab. |
| [setPosition(double value)](#setPosition-double-) | Returns or sets position of a tab. |
| [getAlignment()](#getAlignment--) | Returns or sets align style of a tab. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets align style of a tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares the current instance with another object of the same type. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

إنشاء تبويب جديد

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | double | موضع التبويب. |
| align | int | المحاذاة. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**  
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Returns or sets position of a tab. Assigning this property can change tab's index in collection and invalidate Enumerator. Read/write double.

**الإرجاع:**  
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Returns or sets position of a tab. Assigning this property can change tab's index in collection and invalidate Enumerator. Read/write double.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Returns or sets align style of a tab. Read/write [TabAlignment](../../com.aspose.slides/tabalignment).

**الإرجاع:**  
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Returns or sets align style of a tab. Read/write [TabAlignment](../../com.aspose.slides/tabalignment).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Compares the current instance with another object of the same type.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | An object to compare with this instance. |

**الإرجاع:**  
int - A 32-bit integer that indicates the relative order of the comparands. The return value has these meanings: 

 *  < 0 - هذه الحالة أصغر من obj.  
 *  = 0 - هذه الحالة مساوية لـ obj.  
 *  > 0 - هذه الحالة أكبر من obj.  