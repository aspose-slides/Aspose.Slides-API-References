---
title: NotesSlide
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: प्रस्तुति में एक नोट्स स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/notesslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

एक प्रस्तुति में नोट्स स्लाइड का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getNotesTextFrame()](#getNotesTextFrame--) | यदि नोट्स का पाठ मौजूद हो तो एक TextFrame लौटाता है। |
| [getThemeManager()](#getThemeManager--) | ओवरराइडिंग थीम प्रबंधक लौटाता है। |
| [getParentSlide()](#getParentSlide--) | पैरेंट स्लाइड लौटाता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)।

**रिटर्न:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

यदि नोट्स का पाठ मौजूद हो तो एक TextFrame लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

ओवरराइडिंग थीम प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)।

**रिटर्न:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide)।

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |