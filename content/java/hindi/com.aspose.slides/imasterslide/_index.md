---
title: IMasterSlide
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक प्रस्तुति में मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imasterslide/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)  
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

एक प्रस्तुति में मास्टर स्लाइड का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मास्टर स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getTitleStyle()](#getTitleStyle--) | शीर्षक टेक्स्ट की शैली लौटाता है। |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | वर्तमान स्लाइड के आधार पर एक नया मास्टर स्लाइड बनाता है, उस पर एक बाहरी थीम लागू करता है और बनाए गए मास्टर स्लाइड को सभी आश्रित स्लाइडों पर लागू करता है। |
| [getBodyStyle()](#getBodyStyle--) | बॉडी टेक्स्ट की शैली लौटाता है। |
| [getOtherStyle()](#getOtherStyle--) | अन्य टेक्स्ट की शैली लौटाता है। |
| [getLayoutSlides()](#getLayoutSlides--) | इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। |
| [getPreserve()](#getPreserve--) | निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाए जाती हैं। |
| [setPreserve(boolean value)](#setPreserve-boolean-) | निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाए जाती हैं। |
| [hasDependingSlides()](#hasDependingSlides--) | यदि कम से कम एक स्लाइड इस मास्टर स्लाइड पर निर्भर करती है तो true लौटाता है। |
| [getDependingSlides()](#getDependingSlides--) | उन सभी स्लाइडों का ऐरे लौटाता है, जो इस मास्टर स्लाइड पर निर्भर करती हैं। |
| [getDrawingGuides()](#getDrawingGuides--) | मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

मास्टर स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)।

**रिटर्न:**  
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

शीर्षक टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**रिटर्न:**  
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

वर्तमान स्लाइड के आधार पर एक नया मास्टर स्लाइड बनाता है, उस पर एक बाहरी थीम लागू करता है और बनाए गए मास्टर स्लाइड को सभी आश्रित स्लाइडों पर लागू करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बाहरी थीम फ़ाइल (.thmx) का पथ। |

**रिटर्न:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - नया थीमयुक्त MasterSlide।
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

बॉडी टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**रिटर्न:**  
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

अन्य टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**रिटर्न:**  
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)।

--------------------

आप ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) प्रॉपर्टी का उपयोग करके लेआउट स्लाइड्स को जोड़ने/इन्सर्ट करने/हटाने/क्लोन करने के लिए वैकल्पिक API तक पहुंच सकते हैं।

**रिटर्न:**  
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाए जाती हैं। नोट: Aspose.Slides कभी भी स्वतः कोई अनउपयोगित मास्टर नहीं हटाएगा, वास्तविक रूप से अनउपयोगित मास्टर को हटाने के लिए [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) पढ़ना-लिखना बूलियन।

**रिटर्न:**  
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाए जाती हैं। नोट: Aspose.Slides कभी भी स्वतः कोई अनउपयोगित मास्टर नहीं हटाएगा, वास्तविक रूप से अनउपयोगित मास्टर को हटाने के लिए [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) पढ़ना-लिखना बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

यदि कम से कम एक स्लाइड इस मास्टर स्लाइड पर निर्भर करती है तो true लौटाता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

उन सभी स्लाइडों का ऐरे लौटाता है, जो इस मास्टर स्लाइड पर निर्भर करती हैं।

**रिटर्न:**  
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) का ऐरे, जो इस मास्टर स्लाइड पर निर्भर करती हैं
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // स्लाइड केंद्र के दाएँ तरफ नई ऊर्ध्वाधर ड्रॉइंग गाइड जोड़ना
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)