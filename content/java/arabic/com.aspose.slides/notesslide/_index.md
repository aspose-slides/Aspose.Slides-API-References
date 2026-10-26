---
title: NotesSlide
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل شريحة ملاحظات في عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/notesslide/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

يمثل شريحة ملاحظات في عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير HeaderFooter لشريحة الملاحظات. |
| [getNotesTextFrame()](#getNotesTextFrame--) | يرجع TextFrame يحتوي نص الملاحظات إذا كان موجودًا. |
| [getThemeManager()](#getThemeManager--) | يرجع مدير السمة المتجاوز. |
| [getParentSlide()](#getParentSlide--) | يرجع الشريحة الأصلية. |
| [getShowMasterShapes()](#getShowMasterShapes--) | يحدد ما إذا كان يجب عرض الأشكال على شريحة القالب في الشرائح أم لا. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | يحدد ما إذا كان يجب عرض الأشكال على شريحة القالب في الشرائح أم لا. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```


يرجع مدير HeaderFooter لشريحة الملاحظات. للقراءة فقط [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**الإرجاع:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```


يرجع TextFrame يحتوي نص الملاحظات إذا كان موجودًا. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


يرجع مدير السمة المتجاوز. للقراءة فقط [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**الإرجاع:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```


يرجع الشريحة الأصلية. للقراءة فقط [ISlide](../../com.aspose.slides/islide).

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


يحدد ما إذا كان يجب عرض الأشكال على شريحة القالب في الشرائح أم لا. قراءة/كتابة من نوع boolean.

**الإرجاع:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


يحدد ما إذا كان يجب عرض الأشكال على شريحة القالب في الشرائح أم لا. قراءة/كتابة من نوع boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |