---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides لـ Android عبر مرجع Java API
description: يمثل المدير الذي يحتفظ بسلوك العناصر النائبة بما في ذلك العنصر النائب للرأس لجميع أنواع شرائح النشرات وملاحظات الشرائح.
type: docs
url: /ar/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

يمثل المدير الذي يحتفظ بسلوك العناصر النائبة، بما في ذلك العنصر النائب للرأس لجميع أنواع شرائح النشرات وملاحظات الشرائح.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | يحصل على قيمة تشير إلى وجود عنصر نائب للرأس. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | يغير رؤية عنصر نائب رأس الشريحة. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | يضبط النص لعنصر نائب رأس الشريحة. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


يحصل على قيمة تشير إلى وجود عنصر نائب للرأس. قراءة boolean.

**الإرجاع:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


يغير رؤية عنصر نائب رأس الشريحة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب الرأس مرئياً، وإلا - يخفيه. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


يضبط النص لعنصر نائب رأس الشريحة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |