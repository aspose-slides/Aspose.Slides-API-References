---
title: HyperlinkManager
second_title: Aspose.Slides के लिए Java API संदर्भ
description: हाइपरलिंक प्रबंधन प्रदान करें, जोड़ना और हटाना।
type: docs
url: /hi/com.aspose.slides/hyperlinkmanager/
---
**वंशानुक्रम:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

हाइपरलिंक प्रबंधन प्रदान करें (जोड़ना, हटाना).
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | क्लिक पर बाहरी हाइपरलिंक सेट करें। |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | क्लिक पर आंतरिक हाइपरलिंक सेट करता है। |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | क्लिक पर हाइपरलिंक हटाता है। |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | माउस ओवर पर बाहरी हाइपरलिंक सेट करता है। |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | माउस ओवर पर आंतरिक हाइपरलिंक सेट करता है। |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | माउस ओवर पर हाइपरलिंक हटाता है। |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | क्लिक पर मैक्रो हाइपरलिंक सेट करें। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```


क्लिक पर बाहरी हाइपरलिंक सेट करें।

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // एक Presentation क्लास का उदाहरण बनाता है जो PPTX का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation();
>  try {
>      // प्रस्तुति में पहला स्लाइड प्राप्त करता है
>      ISlide slide = pres.getSlides().get_Item(0);
>      // टाइप को Rectangle सेट करके एक AutoShape ऑब्जेक्ट जोड़ता है
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // shape को AutoShape में कास्ट करता है
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Accesses the ITextFrame property associated with the AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // फ़्रेम में कुछ टेक्स्ट जोड़ता है
>      portion.setText("Aspose.Slides");
>      // portion टेक्स्ट के लिए हाइपरलिंक सेट करता है
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // PPTX प्रस्तुति को सहेजता है
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


क्लिक पर आंतरिक हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | लक्ष्य स्लाइड। |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```


क्लिक पर हाइपरलिंक हटाता है।

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```


माउस ओवर पर बाहरी हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


माउस ओवर पर आंतरिक हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | लक्ष्य स्लाइड। |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```


माउस ओवर पर हाइपरलिंक हटाता है।

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```


क्लिक पर मैक्रो हाइपरलिंक सेट करें।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| macroName | java.lang.String | मैक्रो का नाम |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink ऑब्जेक्ट [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject.

**वापसी:**
com.aspose.slides.IDOMObject