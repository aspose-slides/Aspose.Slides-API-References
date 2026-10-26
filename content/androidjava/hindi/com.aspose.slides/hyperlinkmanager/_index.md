---
title: HyperlinkManager
second_title: Aspose.Slides for Android जावा API संदर्भ के माध्यम से
description: हाइपरलिंक प्रबंधन जोड़ने और हटाने की सुविधा प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/hyperlinkmanager/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

हाइपरलिंक प्रबंधन प्रदान करें (जोड़ना, हटाना)।
## विधियाँ

| विधि | विवरण |
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
>  // PPTX का प्रतिनिधित्व करने वाला Presentation क्लास इंस्टैंसिएट करता है
>  Presentation pres = new Presentation();
>  try {
>      // प्रेज़ेंटेशन में पहली स्लाइड प्राप्त करता है
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Rectangle प्रकार के साथ AutoShape ऑब्जेक्ट जोड़ता है
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // शेप को AutoShape में कैस्ट करता है
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // AutoShape से संबंधित ITextFrame प्रॉपर्टी तक पहुँचता है
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // फ़्रेम में कुछ टेक्स्ट जोड़ता है
>      portion.setText("Aspose.Slides");
>      // पोर्टियन टेक्स्ट के लिए हाइपरलिंक सेट करता है
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // PPTX प्रेज़ेंटेशन को सहेजता है
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | हाइपरलिंक URL। |

**वापसी मान:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

क्लिक पर आंतरिक हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | लक्ष्य स्लाइड। |

**वापसी मान:**
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | हाइपरलिंक URL। |

**वापसी मान:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

माउस ओवर पर आंतरिक हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | लक्षित स्लाइड। |

**वापसी मान:**
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| macroName | java.lang.String | मैक्रो का नाम |

**वापसी मान:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink ऑब्जेक्ट [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent\\_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी मान:**
com.aspose.slides.IDOMObject