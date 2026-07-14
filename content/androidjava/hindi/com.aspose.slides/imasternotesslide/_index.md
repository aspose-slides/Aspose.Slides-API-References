---
title: IMasterNotesSlide
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: नोट्स के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imasternotesslide/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

नोट्स के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मास्टर नोट्स स्लाइड का HeaderFooter मैनेजर लौटाता है। |
| [getNotesStyle()](#getNotesStyle--) | नोट्स टेक्स्ट की शैली लौटाता है। |
| [getDrawingGuides()](#getDrawingGuides--) | मास्टर नोट्स स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


मास्टर नोट्स स्लाइड का HeaderFooter मैनेजर लौटाता है। केवल-पढ़ने योग्य [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)।

**वापसी:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


नोट्स टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**वापसी:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


मास्टर नोट्स स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // स्लाइड के केंद्र के नीचे नया क्षैतिज ड्राइंग गाइड जोड़ना
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)