---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: यह वह प्रबंधक दर्शाता है जो आपको लेआउट स्लाइड में प्लेसहोल्डर जोड़ने की अनुमति देता है।
type: docs
url: /hi/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

यह वह प्रबंधक दर्शाता है जो आपको लेआउट स्लाइड में प्लेसहोल्डर जोड़ने की अनुमति देता है।
## Methods

| मेथड | विवरण |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट रखता है। |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट को ऊर्ध्वाधर दिशा में रखता है। |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री रखता है। |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री को ऊर्ध्वाधर दिशा में रखता है। |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो चित्र रखता है। |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो चार्ट रखता है। |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो तालिका रखता है। |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो स्मार्टआर्ट डायग्राम रखता है। |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो मीडिया ऑब्जेक्ट रखता है। |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो ऑनलाइन इमेज रखता है। |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट रखता है।

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक कंटेंट प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट को ऊर्ध्वाधर दिशा में रखता है।

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक वर्टिकल कंटेंट प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री रखता है।

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक टेक्स्ट प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री को ऊर्ध्वाधर दिशा में रखता है।

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक वर्टिकल टेक्स्ट प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो चित्र रखता है।

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक चित्र प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो चार्ट रखता है।

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक चार्ट प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो तालिका रखता है।

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक टेबल प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो स्मार्टआर्ट डायग्राम रखता है।

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक स्मार्टआर्ट प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो मीडिया ऑब्जेक्ट रखता है।

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक मीडिया प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो ऑनलाइन इमेज रखता है।

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
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
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊंचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - एक ऑनलाइन इमेज प्लेसहोल्डर के साथ [IAutoShape](../../com.aspose.slides/iautoshape) बनाया गया।