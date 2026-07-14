---
title: INotesSlide
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل شريحة ملاحظات في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/inotesslide/
---
**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

يمثل شريحة ملاحظات في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يعيد مدير HeaderFooter الخاص بشريحة الملاحظات. |
| [getNotesTextFrame()](#getNotesTextFrame--) | يعيد TextFrame يحتوي على نص الملاحظات إذا كان موجودًا. |
| [getParentSlide()](#getParentSlide--) | يعيد ParentSlide للقراءة فقط [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

يعيد مدير HeaderFooter الخاص بشريحة الملاحظات. للقراءة فقط [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**القيمة المرتجعة:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

يعيد TextFrame يحتوي على نص الملاحظات إذا كان موجودًا. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**القيمة المرتجعة:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

يعيد ParentSlide للقراءة فقط [ISlide](../../com.aspose.slides/islide).

**القيمة المرتجعة:**  
[ISlide](../../com.aspose.slides/islide)