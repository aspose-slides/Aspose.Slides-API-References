---
title: MasterSlide
second_title: Aspose.Slides Android के लिए Java API संदर्भ
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

| मेथड | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मास्टर स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | वर्तमान स्लाइड पर आधारित नया मास्टर स्लाइड बनाता है, उस पर बाहरी थिम लागू करता है और निर्मित मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है। |
| [getTitleStyle()](#getTitleStyle--) | शीर्षक टेक्स्ट की शैली लौटाता है। |
| [getBodyStyle()](#getBodyStyle--) | बॉडी टेक्स्ट की शैली लौटाता है। |
| [getOtherStyle()](#getOtherStyle--) | अन्य टेक्स्ट की शैली लौटाता है। |
| [getLayoutSlides()](#getLayoutSlides--) | इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। |
| [getPreserve()](#getPreserve--) | निर्धारित करता है कि जब उस मास्टर के बाद सभी स्लाइड्स हटाए जाएँ तो संबंधित मास्टर हटाया जाता है या नहीं। |
| [setPreserve(boolean value)](#setPreserve-boolean-) | निर्धारित करता है कि जब उस मास्टर के बाद सभी स्लाइड्स हटाए जाएँ तो संबंधित मास्टर हटाया जाता है या नहीं। |
| [getDependingSlides()](#getDependingSlides--) | सभी स्लाइड्स के साथ एक एरे लौटाता है, जो इस मास्टर स्लाइड पर निर्भर हैं। |
| [hasDependingSlides()](#hasDependingSlides--) | यदि कम से कम एक स्लाइड इस मास्टर स्लाइड पर निर्भर हो तो true लौटाता है। |
| [getThemeManager()](#getThemeManager--) | थीम मैनेजर लौटाता है। |
| [getName()](#getName--) | मास्टर स्लाइड का नाम लौटाता या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | मास्टर स्लाइड का नाम लौटाता या सेट करता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्देशित करता है कि क्या मास्टर स्लाइड पर शैप्स स्लाइड्स पर दिखाए जाने चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्देशित करता है कि क्या मास्टर स्लाइड पर शैप्स स्लाइड्स पर दिखाए जाने चाहिए या नहीं। |
| [getDrawingGuides()](#getDrawingGuides--) | मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


मास्टर स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**रिटर्न:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


वर्तमान स्लाइड पर आधारित नया मास्टर स्लाइड बनाता है, उस पर बाहरी थिम लागू करता है और निर्मित मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बाहरी थीम फ़ाइल (.thmx) का पथ। |

**रिटर्न:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - नया थीम्ड MasterSlide।
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```


शीर्षक टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```


बॉडी टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```


अन्य टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle).

**रिटर्न:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```


इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

आप ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) प्रॉपर्टी का उपयोग करके लेआउट स्लाइड्स को जोड़ने/इन्सर्ट करने/हटाने/क्लोन करने के वैकल्पिक API तक पहुंच सकते हैं।

**रिटर्न:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```


निर्धारित करता है कि जब उस मास्टर के बाद सभी स्लाइड्स हटाए जाएँ तो संबंधित मास्टर हटाया जाता है या नहीं। नोट: Aspose.Slides स्वयं कभी भी कोई अनउपयोगी मास्टर नहीं हटाएगा, अनउपयोगी मास्टर को वास्तव में हटाने के लिए [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```


निर्धारित करता है कि जब उस मास्टर के बाद सभी स्लाइड्स हटाए जाएँ तो संबंधित मास्टर हटाया जाता है या नहीं। नोट: Aspose.Slides स्वयं कभी भी कोई अनउपयोगी मास्टर नहीं हटाएगा, अनउपयोगी मास्टर को वास्तव में हटाने के लिए [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


मास्टर स्लाइड पर निर्भर सभी स्लाइड्स के साथ एक एरे लौटाता है।

**रिटर्न:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


यदि कम से कम एक स्लाइड इस मास्टर स्लाइड पर निर्भर हो तो true लौटाता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


थीम मैनेजर लौटाता है। केवल-पढ़ने योग्य [IMasterThemeManager](../../com.aspose.slides/imasterthememanager)।

**रिटर्न:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```


मास्टर स्लाइड का नाम लौटाता या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


मास्टर स्लाइड का नाम लौटाता या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


निर्देशित करता है कि क्या मास्टर स्लाइड पर शैप्स स्लाइड्स पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा false लौटाती है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


निर्देशित करता है कि क्या मास्टर स्लाइड पर शैप्स स्लाइड्स पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा false लौटाती है। पढ़ने/लिखने योग्य boolean।

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
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // स्लाइड के केंद्र के दाएँ भाग में नया ऊर्ध्वाधर ड्रॉइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**रिटर्न:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)