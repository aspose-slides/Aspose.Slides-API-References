---
title: IBaseSlideHeaderFooterManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مديرًا يحتفظ بسلوك عناصر نائبة التذييل وتاريخ-الوقت ورقم الصفحة لجميع أنواع الشرائح.
type: docs
url: /ar/com.aspose.slides/ibaseslideheaderfootermanager/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

يمثل مديرًا يحتفظ بسلوك عناصر نائبة التذييل، وتاريخ-الوقت، ورقم الصفحة لجميع أنواع الشرائح.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | يحصل على قيمة تشير إلى وجود عنصر نائب للتذييل. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | يحصل على قيمة تشير إلى وجود عنصر نائب لرقم الصفحة. |
| [isDateTimeVisible()](#isDateTimeVisible--) | يحصل على قيمة تشير إلى وجود عنصر نائب لتاريخ-الوقت. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | يغيّر رؤية عنصر النائب لتذييل الشريحة. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | يغيّر رؤية عنصر النائب لرقم صفحة الشريحة. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | يغيّر رؤية عنصر النائب لتاريخ-الوقت في الشريحة. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | يضبط النص لعنصر النائب لتذييل الشريحة. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | يضبط النص لعنصر النائب لتاريخ-الوقت في الشريحة. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

يحصل على قيمة تشير إلى وجود عنصر نائب للتذييل. قراءة قيمة منطقية.

**القيمة المرجعة:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

يحصل على قيمة تشير إلى وجود عنصر نائب لرقم الصفحة. قراءة قيمة منطقية.

**القيمة المرجعة:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

يحصل على قيمة تشير إلى وجود عنصر نائب لتاريخ-الوقت. قراءة قيمة منطقية.

**القيمة المرجعة:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

يغيّر رؤية عنصر النائب لتذييل الشريحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر النائب للتذييل مرئيًا، وإلا - يخفيه. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

يغيّر رؤية عنصر النائب لرقم صفحة الشريحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر النائب لرقم الصفحة مرئيًا، وإلى - يخفيه. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

يغيّر رؤية عنصر النائب لتاريخ-الوقت في الشريحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر النائب لتاريخ-الوقت مرئيًا، وإلا - يخفيه. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

يضبط النص لعنصر النائب لتذييل الشريحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

يضبط النص لعنصر النائب لتاريخ-الوقت في الشريحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |