---
title: INotesSlide
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक प्रस्तुति में नोट्स स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/inotesslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

एक प्रस्तुति में नोट्स स्लाइड का प्रतिनिधित्व करता है।
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getNotesTextFrame()](#getNotesTextFrame--) | यदि उपलब्ध हो तो नोट्स का टेक्स्ट वाला TextFrame लौटाता है। |
| [getParentSlide()](#getParentSlide--) | ParentSlide केवल-पढ़ने-योग्य [ISlide](../../com.aspose.slides/islide) लौटाता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने-योग्य [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)।

**वापसी:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


यदि उपलब्ध हो तो नोट्स का टेक्स्ट वाला TextFrame लौटाता है। केवल-पढ़ने-योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**वापसी:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


ParentSlide केवल-पढ़ने-योग्य [ISlide](../../com.aspose.slides/islide) लौटाता है।

**वापसी:**
[ISlide](../../com.aspose.slides/islide)