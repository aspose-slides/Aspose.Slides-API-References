---
title: MasterSlide
second_title: जावा के लिए Aspose.Slides API संदर्भ
description: एक प्रस्तुति में मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/masterslide/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

एक प्रस्तुति में मास्टर स्लाइड का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मास्टर स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | वर्तमान स्लाइड के आधार पर एक नई मास्टर स्लाइड बनाता है, उस पर एक बाहरी थीम लागू करता है और बनी हुई मास्टर स्लाइड को सभी निर्भर स्लाइडों पर लागू करता है। |
| [getTitleStyle()](#getTitleStyle--) | शीर्षक पाठ की शैली लौटाता है। |
| [getBodyStyle()](#getBodyStyle--) | मुख्य पाठ की शैली लौटाता है। |
| [getOtherStyle()](#getOtherStyle--) | अन्य पाठ की शैली लौटाता है। |
| [getLayoutSlides()](#getLayoutSlides--) | इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। |
| [getPreserve()](#getPreserve--) | निर्धारित करता है कि सभी स्लाइडों को हटाने पर संबंधित मास्टर हटाया जाता है या नहीं। |
| [setPreserve(boolean value)](#setPreserve-boolean-) | निर्धारित करता है कि सभी स्लाइडों को हटाने पर संबंधित मास्टर हटाया जाता है या नहीं। |
| [getDependingSlides()](#getDependingSlides--) | इस मास्टर स्लाइड पर निर्भर सभी स्लाइडों की एक ऐरे लौटाता है। |
| [hasDependingSlides()](#hasDependingSlides--) | यदि इस मास्टर स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है। |
| [getThemeManager()](#getThemeManager--) | थीम प्रबंधक लौटाता है। |
| [getName()](#getName--) | मास्टर स्लाइड का नाम लौटाता या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | मास्टर स्लाइड का नाम लौटाता या सेट करता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्धारित करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्धारित करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। |
| [getDrawingGuides()](#getDrawingGuides--) | मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

मास्टर स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**वापसी:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

वर्तमान स्लाइड के आधार पर एक नई मास्टर स्लाइड बनाता है, उस पर एक बाहरी थीम लागू करता है और बनी हुई मास्टर स्लाइड को सभी निर्भर स्लाइडों पर लागू करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बाहरी थीम फ़ाइल (.thmx) का पथ। |

**वापसी:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - नया थीमयुक्त MasterSlide।

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

शीर्षक पाठ की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**वापसी:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

मुख्य पाठ की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**वापसी:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

अन्य पाठ की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**वापसी:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

लेआउट स्लाइड्स को जोड़ने/डालने/हटाने/क्लोन करने के लिए वैकल्पिक API तक आप ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) प्रॉपर्टी का उपयोग करके पहुँच सकते हैं।

**वापसी:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

निर्धारित करता है कि सभी स्लाइडों को हटाने पर संबंधित मास्टर हटाया जाता है या नहीं। ध्यान दें: Aspose.Slides खुद से कोई भी अप्रयुक्त मास्टर नहीं हटाएगा, वास्तविक में अप्रयुक्त मास्टर हटाने के लिए [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) पढ़ने/लिखने योग्य boolean ।

**वापसी:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

निर्धारित करता है कि सभी स्लाइडों को हटाने पर संबंधित मास्टर हटाया जाता है या नहीं। ध्यान दें: Aspose.Slides खुद से कोई भी अप्रयुक्त मास्टर नहीं हटाएगा, वास्तविक में अप्रयुक्त मास्टर हटाने के लिए [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

इस मास्टर स्लाइड पर निर्भर सभी स्लाइडों की एक ऐरे लौटाता है।

**वापसी:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) का ऐरे

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

यदि इस मास्टर स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है। केवल-पढ़ने योग्य boolean .

**वापसी:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

थीम प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**वापसी:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

मास्टर स्लाइड का नाम लौटाता या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

मास्टर स्लाइड का नाम लौटाता या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा false लौटाता है। पढ़ने/लिखने योग्य boolean .

**वापसी:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

निर्दिष्ट करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा false लौटाता है। पढ़ने/लिखने योग्य boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // स्लाइड केंद्र के दाएँ हिस्से में नई लंबवत ड्रॉइंग गाइड जोड़ना
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)