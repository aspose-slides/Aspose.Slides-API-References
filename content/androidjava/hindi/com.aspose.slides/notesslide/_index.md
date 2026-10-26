---
title: NotesSlide
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रस्तुति में एक नोट्स स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/notesslide/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

एक प्रस्तुति में नोट्स स्लाइड का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Notes स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getNotesTextFrame()](#getNotesTextFrame--) | यदि उपलब्ध हो तो नोट्स के पाठ के साथ एक TextFrame लौटाता है। |
| [getThemeManager()](#getThemeManager--) | ओवरराइडिंग थीम प्रबंधक लौटाता है। |
| [getParentSlide()](#getParentSlide--) | पैरेंट स्लाइड लौटाता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्देशित करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्देशित करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाए या नहीं। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Returns HeaderFooter manager of the notes slide. Read-only [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**वापसी:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Returns a TextFrame with notes' text if there is one. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Returns the overriding theme manager. Read-only [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**वापसी:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Returns the parent slide. Read-only [ISlide](../../com.aspose.slides/islide).

**वापसी:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean.

**वापसी:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specifies

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |