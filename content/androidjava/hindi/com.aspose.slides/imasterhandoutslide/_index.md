---
title: IMasterHandoutSlide
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस
description: हैंडआउट के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imasterhandoutslide/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

हैंडआउट के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मास्टर हैंडआउट स्लाइड का HeaderFooter मैनेजर लौटाता है। |
| [getDrawingGuides()](#getDrawingGuides--) | मास्टर हैंडआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

मास्टर हैंडआउट स्लाइड का HeaderFooter मैनेजर लौटाता है। केवल पढ़ने योग्य [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**वापसी:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

मास्टर हैंडआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // स्लाइड केंद्र के ऊपर नया क्षैतिज ड्रॉइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)