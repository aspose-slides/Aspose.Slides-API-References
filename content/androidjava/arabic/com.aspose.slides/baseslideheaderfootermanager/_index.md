---
title: BaseSlideHeaderFooterManager
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مديرًا يحتفظ بسلوك العناصر النائبة للتذييل وتاريخ/الوقت ورقم الصفحة لجميع أنواع الشرائح.
type: docs
url: /ar/com.aspose.slides/baseslideheaderfootermanager/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)  
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

يمثل مديرًا يحتفظ بسلوك العناصر النائبة للتذييل، وتاريخ/وقت، ورقم الصفحة لجميع أنواع الشرائح.  

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | يحصل على القيمة التي تشير إلى وجود عنصر ناطق للتذييل. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | يحصل على القيمة التي تشير إلى وجود عنصر ناطق لرقم الصفحة. |
| [isDateTimeVisible()](#isDateTimeVisible--) | يحصل على القيمة التي تشير إلى وجود عنصر ناطق لتاريخ/وقت. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | يغيّر رؤية عنصر ناطق للتذييل في الشريحة. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | يغيّر رؤية عنصر ناطق لرقم الصفحة في الشريحة. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | يغيّر رؤية عنصر ناطق لتاريخ/وقت في الشريحة. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | يضبط النص لعنصر ناطق للتذييل في الشريحة. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | يضبط النص لعنصر ناطق لتاريخ/وقت في الشريحة. |

### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

يحصل على القيمة التي تشير إلى وجود عنصر ناطق للتذييل. قراءة من نوع boolean.

**الإرجاع:**  
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

يحصل على القيمة التي تشير إلى وجود عنصر ناطق لرقم الصفحة. قراءة من نوع boolean.

**الإرجاع:**  
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

يحصل على القيمة التي تشير إلى وجود عنصر ناطق لتاريخ/وقت. قراءة من نوع boolean.

**الإرجاع:**  
boolean

### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

يغيّر رؤية عنصر ناطق للتذييل في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر ناطق للتذييل مرئيًا، وإلا - يخفيه. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

يغيّر رؤية عنصر ناطق لرقم الصفحة في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر ناطق لرقم الصفحة مرئيًا، وإلا - يخفيه. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

يغيّر رؤية عنصر ناطق لتاريخ/وقت في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر ناطق لتاريخ/وقت مرئيًا، وإلا - يخفيه. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

يضبط النص لعنصر ناطق للتذييل في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

يضبط النص لعنصر ناطق لتاريخ/وقت في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |