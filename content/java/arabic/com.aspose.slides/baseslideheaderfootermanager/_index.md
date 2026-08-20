---
title: BaseSlideHeaderFooterManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مديرًا يحتفظ بسلوك عناصر النائب للتذييل والوقت/التاريخ ورقم الصفحة لجميع أنواع الشرائح.
type: docs
url: /ar/com.aspose.slides/baseslideheaderfootermanager/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

يمثل مديرًا يحتفظ بسلوك عناصر النائب للتذييل، والوقت/التاريخ، ورقم الصفحة لجميع أنواع الشرائح.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | يحصل على قيمة تشير إلى أن عنصر نائب للتذييل موجود. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | يحصل على قيمة تشير إلى أن عنصر نائب لرقم الصفحة موجود. |
| [isDateTimeVisible()](#isDateTimeVisible--) | يحصل على قيمة تشير إلى أن عنصر نائب للوقت/التاريخ موجود. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | يغير رؤية عنصر نائب للتذييل في الشريحة. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | يغير رؤية عنصر نائب لرقم الصفحة في الشريحة. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | يغير رؤية عنصر نائب للوقت/التاريخ في الشريحة. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | يضبط النص لعنصر نائب التذييل في الشريحة. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | يضبط النص لعنصر نائب الوقت/التاريخ في الشريحة. |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

يحصل على قيمة تشير إلى أن عنصر نائب للتذييل موجود. قراءة منطقية.

**القيمة المرجعة:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

يحصل على قيمة تشير إلى أن عنصر نائب لرقم الصفحة موجود. قراءة منطقية.

**القيمة المرجعة:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

يحصل على قيمة تشير إلى أن عنصر نائب للوقت/التاريخ موجود. قراءة منطقية.

**القيمة المرجعة:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

يغير رؤية عنصر نائب للتذييل في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب للتذييل مرئيًا، وإلا - يخفيه. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

يغير رؤية عنصر نائب لرقم الصفحة في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب لرقم الصفحة مرئيًا، وإلا - يخفيه. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

يغير رؤية عنصر نائب للوقت/التاريخ في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب للوقت/التاريخ مرئيًا، وإلا - يخفيه. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

يضبط النص لعنصر نائب التذييل في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

يضبط النص لعنصر نائب الوقت/التاريخ في الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |