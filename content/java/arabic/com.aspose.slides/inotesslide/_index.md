---
title: INotesSlide
second_title: Aspose.Slides ل Java مرجع API
description: يمثل شريحة ملاحظات في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/inotesslide/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

يمثل شريحة ملاحظات في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير HeaderFooter لشريحة الملاحظات. |
| [getNotesTextFrame()](#getNotesTextFrame--) | يرجع TextFrame يحتوي نص الملاحظات إذا وجد. |
| [getParentSlide()](#getParentSlide--) | يرجع ParentSlide للقراءة فقط [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter لشريحة الملاحظات. للقراءة فقط [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**القيمة المرجعة:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

يرجع TextFrame يحتوي نص الملاحظات إذا وجد. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

يرجع ParentSlide للقراءة فقط [ISlide](../../com.aspose.slides/islide).

**القيمة المرجعة:**
[ISlide](../../com.aspose.slides/islide)