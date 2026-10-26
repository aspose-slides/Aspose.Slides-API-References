---
title: MasterHandoutSlide
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API संदर्भ के माध्यम से
description: हैंडआउट्स के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।
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

हैंडआउट्स के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | यह निर्दिष्ट करता है कि क्या मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | यह निर्दिष्ट करता है कि क्या मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मास्टर हैंडआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getThemeManager()](#getThemeManager--) | थीम प्रबंधक लौटाता है। |
| [getDrawingGuides()](#getDrawingGuides--) | मास्टर हैंडआउट स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

यह निर्दिष्ट करता है कि क्या मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा false लौटाती है। पढ़ें/लिखें बूलियन।

**वापसी:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

यह निर्दिष्ट करता है कि क्या मास्टर स्लाइड पर आकृतियों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा false लौटाती है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

मास्टर हैंडआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल पढ़ने योग्य [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)।

**वापसी:**  
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

थीम प्रबंधक लौटाता है। केवल पढ़ने योग्य [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)।

**वापसी:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

मास्टर हैंडआउट स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // स्लाइड केंद्र के ऊपर नई क्षैतिज ड्रॉइंग गाइड जोड़ना
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)