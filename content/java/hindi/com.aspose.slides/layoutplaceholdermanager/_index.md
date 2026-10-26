---
title: LayoutPlaceholderManager
second_title: Aspose.Slides जावा API संदर्भ
description: एक प्रबंधक को दर्शाता है जो आपको लेआउट स्लाइड में प्लेसहोल्डर जोड़ने की अनुमति देता है।
type: docs
url: /hi/com.aspose.slides/layoutplaceholdermanager/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

ऐसा प्रबंधक दर्शाता है जो आपको लेआउट स्लाइड में प्लेसहोल्डर जोड़ने की अनुमति देता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या पाठ, रखता है। |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या पाठ, लंबवत दिशा में रखता है। |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो पाठ सामग्री रखता है। |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो पाठ सामग्री को लंबवत दिशा में रखता है। |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक चित्र रखता है। |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक चार्ट रखता है। |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक तालिका रखता है। |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक SmartArt आरेख रखता है। |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक मीडिया ऑब्जेक्ट रखता है। |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक ऑनलाइन छवि रखता है। |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या पाठ, रखता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Content प्लेसहोल्डर आकार कैसे जोड़ें।
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Content प्लेसहोल्डर के साथ।
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या पाठ, लंबवत दिशा में रखता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Content (Vertical) प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Content (Vertical) प्लेसहोल्डर के साथ।
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो पाठ सामग्री रखता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Text प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Text प्लेसहोल्डर के साथ।
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो पाठ सामग्री को लंबवत दिशा में रखता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Text (Vertical) प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Text (Vertical) प्लेसहोल्डर के साथ।
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक चित्र रखता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Picture प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Picture प्लेसहोल्डर के साथ।
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक चार्ट रखता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Chart प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Chart प्लेसहोल्डर के साथ।
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक तालिका रखता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में Table प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Table प्लेसहोल्डर के साथ।
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक SmartArt आरेख रखता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि लेआउट स्लाइड में SmartArt प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक SmartArt प्लेसहोल्डर के साथ।
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक मीडिया ऑब्जेक्ट रखता है।

--------------------

> ``` 
> निम्न उदाहरण दर्शाता है कि लेआउट स्लाइड में Media प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Media प्लेसहोल्डर के साथ।
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नया प्लेसहोल्डर आकार जोड़ता है जो एक ऑनलाइन छवि रखता है।

--------------------

> ```
> निम्न उदाहरण दर्शाता है कि लेआउट स्लाइड में Online Image प्लेसहोल्डर आकार कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X निर्देशांक। |
| y | float | नए प्लेसहोल्डर आकार का Y निर्देशांक। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Online Image प्लेसहोल्डर के साथ।