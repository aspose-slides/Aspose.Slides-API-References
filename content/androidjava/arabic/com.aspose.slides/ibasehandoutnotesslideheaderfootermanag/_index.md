---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مديرًا يحتفظ بسلوك العناصر النائبة، بما في ذلك عنصر نائب الرأس لجميع أنواع الشرائح (التوزيعية وملاحظات الشرائح).
type: docs
url: /ar/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

يمثل مديرًا يحتفظ بسلوك العناصر النائبة، بما في ذلك عنصر نائب رأس لجميع أنواع الشرائح (النسخ الموزعة وملاحظات الشرائح).

--------------------

اسم الواجهة الأصلي "IBaseHandoutNotesSlideHeaderFooterManager" تم تقصيره إلى "IBaseHandoutNotesSlideHeaderFooterManag" لتوافق COM (يجب ألا يتجاوز طول اسم النوع 39).
## الطرق

| Method | Description |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | يحصل على القيمة التي تشير إلى وجود عنصر نائب رأس. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | يغيّر ظهور عنصر نائب رأس الشريحة. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | يضبط النص لعنصر نائب رأس الشريحة. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

يحصل على القيمة التي تشير إلى وجود عنصر نائب رأس. قراءة Boolean.

**Returns:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

يغيّر ظهور عنصر نائب رأس الشريحة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - يجعل عنصر نائب الرأس مرئيًا، وإلا يُخفيه. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

يضبط النص لعنصر نائب رأس الشريحة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | النص المراد تعيينه. |