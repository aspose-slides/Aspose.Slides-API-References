---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: हाइपरलिंक प्रबंधन प्रदान करता है, जोड़ना और हटाना।
type: docs
url: /hi/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

हाइपरलिंक प्रबंधन (जोड़ना, हटाना)।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | क्लिक करने पर बाहरी हाइपरलिंक सेट करता है। |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | क्लिक करने पर आंतरिक हाइपरलिंक सेट करता है। |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | क्लिक करने पर हाइपरलिंक हटाता है। |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | माउस ओवर करने पर बाहरी हाइपरलिंक सेट करता है। |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | माउस ओवर करने पर आंतरिक हाइपरलिंक सेट करता है। |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | माउस ओवर करने पर हाइपरलिंक हटाता है। |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | क्लिक करने पर मैक्रो हाइपरलिंक सेट करता है। |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

क्लिक करने पर बाहरी हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | हाइपरलिंक URL। |

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक ऑब्जेक्ट [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

क्लिक करने पर आंतरिक हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | लक्षित स्लाइड। |

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक।
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

क्लिक करने पर हाइपरलिंक हटाता है।

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

माउस ओवर करने पर बाहरी हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | हाइपरलिंक URL। |

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक।
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

माउस ओवर करने पर आंतरिक हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | लक्षित स्लाइड। |

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक।
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

माउस ओवर करने पर हाइपरलिंक हटाता है।

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

क्लिक करने पर मैक्रो हाइपरलिंक सेट करता है।

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

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक ऑब्जेक्ट [IHyperlink](../../com.aspose.slides/ihyperlink)