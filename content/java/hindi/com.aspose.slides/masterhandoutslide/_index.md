---
title: MasterHandoutSlide
second_title: Aspose.Slides for Java API संदर्भ
description: हैंडआउट के लिए मुख्य स्लाइड को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/masterhandoutslide/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

हैंडआउट के लिए मुख्य स्लाइड को दर्शाता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्दिष्ट करता है कि मुख्य स्लाइड पर आकारों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्दिष्ट करता है कि मुख्य स्लाइड पर आकारों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मुख्य हैंडआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getThemeManager()](#getThemeManager--) | थीम प्रबंधक लौटाता है। |
| [getDrawingGuides()](#getDrawingGuides--) | मुख्य हैंडआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

निर्दिष्ट करता है कि मुख्य स्लाइड पर आकारों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। मुख्य स्लाइड के लिए यह गुण हमेशा false लौटाता है। पढ़ें/लिखें बूलियन।

**रिटर्न:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

निर्दिष्ट करता है कि मुख्य स्लाइड पर आकारों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। मुख्य स्लाइड के लिए यह गुण हमेशा false लौटाता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

मुख्य हैंडआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल पढ़ने योग्य [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)।

**रिटर्न:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

थीम प्रबंधक लौटाता है। केवल पढ़ने योग्य [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)।

**रिटर्न:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

मुख्य हैंडआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // स्लाइड के केंद्र के ऊपर नया क्षैतिज ड्राइंग गाइड जोड़ें
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)