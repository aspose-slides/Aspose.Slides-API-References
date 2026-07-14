---
title: NotesSlide
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل شريحة ملاحظات في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/notesslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Represents a notes slide in a presentation.
## الطرق

| طريقة | وصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير HeaderFooter لشريحة الملاحظات. |
| [getNotesTextFrame()](#getNotesTextFrame--) | يرجع TextFrame يحتوي نص الملاحظات إذا كان موجودًا. |
| [getThemeManager()](#getThemeManager--) | يرجع مدير الثيم المتجاوز. |
| [getParentSlide()](#getParentSlide--) | يرجع الشريحة الأم. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان ينبغي إظهار الأشكال على الشريحة الرئيسة في الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان ينبغي إظهار الأشكال على الشريحة الرئيسة في الشرائح أم لا. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter لشريحة الملاحظات. للقراءة فقط [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**القيمة المرجعة:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

يرجع TextFrame يحتوي نص الملاحظات إذا كان موجودًا. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**القيمة المرجعة:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

يرجع مدير الثيم المتجاوز. للقراءة فقط [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**القيمة المرجعة:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

يرجع الشريحة الأم. للقراءة فقط [ISlide](../../com.aspose.slides/islide).

**القيمة المرجعة:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

يحدد ما إذا كان ينبغي إظهار الأشكال على الشريحة الرئيسة في الشرائح أم لا. قراءة/كتابة منطقية.

**القيمة المرجعة:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

يحدد ما إذا كان ينبغي إظهار الأشكال على الشريحة الرئيسة في الشرائح أم لا. قراءة/كتابة منطقية.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | boolean |  |