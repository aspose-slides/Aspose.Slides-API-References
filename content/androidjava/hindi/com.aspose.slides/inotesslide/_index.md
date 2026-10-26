---
title: INotesSlide
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रस्तुति में एक नोट्स स्लाइड को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/inotesslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

एक प्रस्तुति में नोट्स स्लाइड को दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getNotesTextFrame()](#getNotesTextFrame--) | यदि उपलब्ध हो तो नोट्स के टेक्स्ट के साथ एक TextFrame लौटाता है। |
| [getParentSlide()](#getParentSlide--) | एक ParentSlide केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide) लौटाता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)।

**वापसी:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

यदि उपलब्ध हो तो नोट्स के टेक्स्ट के साथ एक TextFrame लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

एक ParentSlide केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide) लौटाता है।

**वापसी:**
[ISlide](../../com.aspose.slides/islide)