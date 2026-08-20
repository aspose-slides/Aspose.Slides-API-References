---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة Java
description: يمثّل مديرًا يحتفظ بسلوك العناصر النائبة، بما في ذلك العنصر النائب لرأس الصفحة لجميع أنواع شرائح الملاحظات ونسخ التوزيع.
type: docs
url: /ar/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

يمثّل مديرًا يحتفظ بسلوك العناصر النائبة، بما في ذلك عنصر النائب لرأس الصفحة لجميع أنواع شرائح الملاحظات ونسخ التوزيع.

--------------------

تم تقصير اسم الواجهة الأصلية "IBaseHandoutNotesSlideHeaderFooterManager" إلى "IBaseHandoutNotesSlideHeaderFooterManag" لتوافق COM (يجب ألا يتجاوز طول اسم النوع 39).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | يحصل على قيمة تُشير إلى وجود عنصر نائب لرأس الصفحة. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | يغيّر رؤية عنصر نائب رأس الصفحة للشريحة. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | يضبط النص لعنصر نائب رأس الصفحة في الشريحة. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


يحصل على قيمة تُشير إلى وجود عنصر نائب لرأس الصفحة. قراءة منطقية.

**الإرجاع:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


يغيّر رؤية عنصر نائب رأس الصفحة للشريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر النائب للرأس مرئيًا، وإلا - يخفيه. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


يضبط النص لعنصر نائب رأس الصفحة في الشريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد ضبطه. |