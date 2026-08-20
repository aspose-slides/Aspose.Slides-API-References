---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مديرًا يحتوي على سلوك العناصر النائبة بما في ذلك عنصر نائب رأس لجميع أنواع الشرائح اليدوية وملاحظات الشرائح.
type: docs
url: /ar/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

يمثل مديرًا يحتوي على سلوك العناصر النائبة، بما في ذلك عنصر نائب رأس للنوعين كتيب الملاحظات وشريحة الملاحظات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | يحصل على قيمة تشير إلى وجود عنصر نائب للرأس. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | يغيّر إظهار عنصر نائب رأس الشريحة. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | يضبط النص لعنصر نائب رأس الشريحة. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


يحصل على قيمة تشير إلى وجود عنصر نائب للرأس. قراءة منطقية.

**القيمة المرجعة:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


يغيّر إظهار عنصر نائب رأس الشريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب الرأس مرئيًا، وإلا - يخفيه. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


يضبط النص لعنصر نائب رأس الشريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |