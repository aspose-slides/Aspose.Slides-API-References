---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل المدير الذي يحمل سلوك عناصر نائب التذييل والتاريخ/الوقت ورقم الصفحة لجميع أنواع الشرائح.
type: docs
url: /ar/com.aspose.slides/ibaseslideheaderfootermanager/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

يمثل المدير الذي يحتفظ بسلوك عناصر نائب التذييل، التاريخ/الوقت، ورقم الصفحة لجميع أنواع الشرائح.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | يحصل على القيمة التي تشير إلى وجود عنصر نائب للتذييل. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | يحصل على القيمة التي تشير إلى وجود عنصر نائب لرقم الصفحة. |
| [isDateTimeVisible()](#isDateTimeVisible--) | يحصل على القيمة التي تشير إلى وجود عنصر نائب للوقت/التاريخ. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | يغيّر رؤية عنصر نائب التذييل في الشريحة. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | يغيّر رؤية عنصر نائب رقم الصفحة في الشريحة. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | يغيّر رؤية عنصر نائب التاريخ/الوقت في الشريحة. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | يضبط النص لعنصر نائب التذييل في الشريحة. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | يضبط النص لعنصر نائب التاريخ/الوقت في الشريحة. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


يحصل على القيمة التي تشير إلى وجود عنصر نائب للتذييل. قراءة منطقية.

**الإرجاع:**  
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


يحصل على القيمة التي تشير إلى وجود عنصر نائب لرقم الصفحة. قراءة منطقية.

**الإرجاع:**  
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


يحصل على القيمة التي تشير إلى وجود عنصر نائب للوقت/التاريخ. قراءة منطقية.

**الإرجاع:**  
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


يغيّر رؤية عنصر نائب التذييل في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب التذييل مرئياً، وإلا - يخفيه. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


يغيّر رؤية عنصر نائب رقم الصفحة في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب رقم الصفحة مرئياً، وإلا - يخفيه. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


يغيّر رؤية عنصر نائب التاريخ/الوقت في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب التاريخ/الوقت مرئياً، وإلا - يخفيه. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


يضبط النص لعنصر نائب التذييل في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


يضبط النص لعنصر نائب التاريخ/الوقت في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |