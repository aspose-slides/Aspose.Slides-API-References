---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /hi/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

लेआउट स्लाइड में प्लेसहोल्डर जोड़ने की अनुमति देने वाला मैनेजर दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट, को रखता है। |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट, को एक लंबवत दिशा में रखता है। |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री को रखता है। |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री को एक लंबवत दिशा में रखता है। |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक चित्र को रखता है। |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक चार्ट को रखता है। |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक तालिका को रखता है। |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक SmartArt डायग्राम को रखता है। |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक मीडिया ऑब्जेक्ट को रखता है। |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक ऑनलाइन इमेज को रखता है। |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट, को रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Content प्लेसहोल्डर के साथ।
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो सामग्री, जैसे चित्र, तालिका, मीडिया या टेक्स्ट, को एक लंबवत दिशा में रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Content (Vertical) प्लेसहोल्डर के साथ।
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री को रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Text प्लेसहोल्डर के साथ।
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो टेक्स्ट सामग्री को एक लंबवत दिशा में रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Text (Vertical) प्लेसहोल्डर के साथ।
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक चित्र को रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Picture प्लेसहोल्डर के साथ।
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक चार्ट को रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Chart प्लेसहोल्डर के साथ।
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक तालिका को रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Table प्लेसहोल्डर के साथ।
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक SmartArt डायग्राम को रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक SmartArt प्लेसहोल्डर के साथ।
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक मीडिया ऑब्जेक्ट को रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Media प्लेसहोल्डर के साथ।
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


लेआउट स्लाइड में एक नया प्लेसहोल्डर आकार जोड़ता है जो एक ऑनलाइन इमेज को रखता है।

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
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**
[IAutoShape](../../com.aspose.slides/iautoshape) - निर्मित [IAutoShape](../../com.aspose.slides/iautoshape) एक Online Image प्लेसहोल्डर के साथ।