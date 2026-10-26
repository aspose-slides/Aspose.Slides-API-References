---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API संदर्भ
description: हाइपरलिंक प्रबंधन (जोड़ने, हटाने) प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

हाइपरलिंक प्रबंधन (जोड़ना, हटाना) प्रदान करता है।

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

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

क्लिक पर बाहरी हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | हाइपरलिंक URL। |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक ऑब्जेक्ट [IHyperlink](../../com.aspose.slides/ihyperlink)

### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

क्लिक पर आंतरिक हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | लक्षित स्लाइड। |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक।

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

क्लिक पर हाइपरलिंक हटाता है।

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

माउस ओवर पर बाहरी हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | हाइपरलिंक URL। |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक।

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

माउस ओवर पर आंतरिक हाइपरलिंक सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | लक्षित स्लाइड। |

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक।

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

माउस ओवर पर हाइपरलिंक हटाता है।

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
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

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - हाइपरलिंक ऑब्जेक्ट [IHyperlink](../../com.aspose.slides/ihyperlink)