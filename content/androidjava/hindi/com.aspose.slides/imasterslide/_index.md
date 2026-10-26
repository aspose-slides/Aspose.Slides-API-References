---
title: IMasterSlide
second_title: Aspose.Slides Android के लिए Java API संदर्भ
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

| मेथड | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | मास्टर स्लाइड का HeaderFooter प्रबंधक वापस करता है। |
| [getTitleStyle()](#getTitleStyle--) | शीर्षक पाठ की शैली वापस करता है। |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | वर्तमान मास्टर स्लाइड के आधार पर एक नई मास्टर स्लाइड बनाता है, एक बाहरी थीम लागू करता है और बनाई गई मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है। |
| [getBodyStyle()](#getBodyStyle--) | बॉडी टेक्स्ट की शैली वापस करता है। |
| [getOtherStyle()](#getOtherStyle--) | अन्य पाठ की शैली वापस करता है। |
| [getLayoutSlides()](#getLayoutSlides--) | इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह वापस करता है। |
| [getPreserve()](#getPreserve--) | निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाई जाती हैं। |
| [setPreserve(boolean value)](#setPreserve-boolean-) | निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाई जाती हैं। |
| [hasDependingSlides()](#hasDependingSlides--) | यदि इस मास्टर स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है। |
| [getDependingSlides()](#getDependingSlides--) | एक ऐरे लौटाता है जिसमें सभी स्लाइड्स होंगी, जो इस मास्टर स्लाइड पर निर्भर करती हैं। |
| [getDrawingGuides()](#getDrawingGuides--) | मास्टर स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

मास्टर स्लाइड का HeaderFooter प्रबंधक वापस करता है। केवल-पढ़ने योग्य [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)।

**वापसी:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

शीर्षक पाठ की शैली वापस करता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**वापसी:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

वर्तमान मास्टर स्लाइड के आधार पर एक नई मास्टर स्लाइड बनाता है, एक बाहरी थीम लागू करता है और बनाई गई मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fname | java.lang.String | बाहरी थीम फ़ाइल (.thmx) का पाथ। |

**वापसी:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - नई थीम वाली MasterSlide.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

बॉडी टेक्स्ट की शैली वापस करता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**वापसी:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

अन्य पाठ की शैली वापस करता है। केवल-पढ़ने योग्य [ITextStyle](../../com.aspose.slides/itextstyle)।

**वापसी:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह वापस करता है। केवल-पढ़ने योग्य [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)।

--------------------

आप ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) प्रॉपर्टी का उपयोग करके लेआउट स्लाइड्स को जोड़ने/डालने/हटाने/क्लोन करने के लिए वैकल्पिक API तक पहुंच सकते हैं।

**वापसी:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाई जाती हैं। नोट: Aspose.Slides स्वयं कोई भी अप्रयुक्त मास्टर नहीं हटाएगा, अप्रयुक्त मास्टर्स को वास्तव में हटाने के लिए [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) को कॉल करें पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाई जाती हैं। नोट: Aspose.Slides स्वयं कोई भी अप्रयुक्त मास्टर नहीं हटाएगा, अप्रयुक्त मास्टर्स को वास्तव में हटाने के लिए [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) को कॉल करें पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

यदि इस मास्टर स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है। केवल-पढ़ने योग्य बूलियन।

**वापसी:**
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

एक ऐरे लौटाता है जिसमें सभी स्लाइड्स होंगी, जो इस मास्टर स्लाइड पर निर्भर करती हैं।

**वापसी:**
com.aspose.slides.ISlide[] - ऐरे ऑफ [ISlide](../../com.aspose.slides/islide), जो इस मास्टर स्लाइड पर निर्भर करती हैं

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

मास्टर स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // स्लाइड केंद्र के दाईं ओर नया लंबवत ड्राइंग गाइड जोड़ना
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)