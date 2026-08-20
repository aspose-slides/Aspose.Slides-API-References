---
title: MasterNotesSlide
second_title: Aspose.Slides for Java API संदर्भ
description: नोट्स के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/masternotesslide/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

नोट्स के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।
## विधाएँ

| मेथड | विवरण |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मास्टर नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getThemeManager()](#getThemeManager--) | थीम प्रबंधक लौटाता है। |
| [getNotesStyle()](#getNotesStyle--) | नोट्स टेक्स्ट की शैली लौटाता है। |
| [getDrawingGuides()](#getDrawingGuides--) | मास्टर नोट्स स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। मास्टर स्लाइड स्वयं के लिए यह प्रॉपर्टी हमेशा false लौटाती है। Read/write boolean.

**रिटर्न:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। मास्टर स्लाइड स्वयं के लिए यह प्रॉपर्टी हमेशा false लौटाती है। Read/write boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


मास्टर नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। Read-only [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)।

**रिटर्न:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


थीम प्रबंधक लौटाता है। Read-only [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)।

**रिटर्न:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```


नोट्स टेक्स्ट की शैली लौटाता है। Read-only [ITextStyle](../../com.aspose.slides/itextstyle)।

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


मास्टर नोट्स स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। Read-only [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // स्लाइड केंद्र के नीचे नया क्षैतिज ड्रॉइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)