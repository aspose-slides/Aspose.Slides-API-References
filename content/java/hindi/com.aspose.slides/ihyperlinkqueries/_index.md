---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: निहित हाइपरलिंक तक आसान पहुंच प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

निहित हाइपरलिंक तक आसान पहुंच प्रदान करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | सभी IHyperlinkContainer उपवस्तुओं को प्राप्त करें जिनमें गैर-नल HyperlinkClick है। |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | सभी IHyperlinkContainer उपवस्तुओं को प्राप्त करें जिनमें गैर-नल HyperlinkMouseOver है। |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | सभी IHyperlinkContainer उपवस्तुओं को प्राप्त करें जिनमें गैर-नल HyperlinkMouseOver है। |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | सभी निहित HyperlinkClick और HyperlinkMouseOver हाइपरलिंक को हटाता है (सभी IHyperlinkContainer उपवस्तुओं में)। |

### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

सभी IHyperlinkContainer उपवस्तुओं को प्राप्त करें जिनमें गैर-नल HyperlinkClick है। दिए गए IHyperlinkContainer ऑब्जेक्ट के साथ आप उसके हाइपरलिंक को प्रबंधित कर सकते हैं (पढ़ना, अपडेट करना या हटाना)। IHyperlinkContainer इंटरफ़ेस देखें।

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - सभी IHyperlinkContainer उपवस्तुएँ जिनमें गैर-नल HyperlinkClick है

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

सभी IHyperlinkContainer उपवस्तुओं को प्राप्त करें जिनमें गैर-नल HyperlinkMouseOver है। दिए गए IHyperlinkContainer ऑब्जेक्ट के साथ आप उसके हाइपरलिंक को प्रबंधित कर सकते हैं (पढ़ना, अपडेट करना या हटाना)। IHyperlinkContainer इंटरफ़ेस देखें।

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - सभी IHyperlinkContainer उपवस्तुएँ जिनमें गैर-नल HyperlinkMouseOver है

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

सभी IHyperlinkContainer उपवस्तुओं को प्राप्त करें जिनमें गैर-नल HyperlinkMouseOver है। दिए गए IHyperlinkContainer ऑब्जेक्ट के साथ आप उसके हाइपरलिंक को प्रबंधित कर सकते हैं (पढ़ना, अपडेट करना या हटाना)। IHyperlinkContainer इंटरफ़ेस देखें।

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - सभी IHyperlinkContainer उपवस्तुएँ जिनमें गैर-नल HyperlinkMouseOver है

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

सभी निहित HyperlinkClick और HyperlinkMouseOver हाइपरलिंक को हटाता है (सभी IHyperlinkContainer उपवस्तुओं में)।