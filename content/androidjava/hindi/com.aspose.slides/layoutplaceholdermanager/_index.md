---
title: LayoutPlaceholderManager
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
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

एक प्रबंधक को दर्शाता है जो आपको लेआउट स्लाइड में प्लेसहोल्डर जोड़ने की अनुमति देता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो सामग्री रखता है, जैसे कि चित्र, तालिका, मीडिया या पाठ। |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो सामग्री रखता है, जैसे कि चित्र, तालिका, मीडिया या पाठ, एक ऊर्ध्वाधर दिशा में। |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो पाठ सामग्री रखता है। |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो पाठ सामग्री, एक ऊर्ध्वाधर दिशा में। |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक चित्र रखता है। |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक चार्ट रखता है। |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक तालिका रखता है। |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक SmartArt आकृति रखता है। |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक मीडिया ऑब्जेक्ट रखता है। |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक ऑनलाइन छवि रखता है। |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो सामग्री रखता है, जैसे कि चित्र, तालिका, मीडिया या पाठ।

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a Content placeholder.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो सामग्री रखता है, जैसे कि चित्र, तालिका, मीडिया या पाठ, एक ऊर्ध्वाधर दिशा में।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a Content (Vertical) placeholder.

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो पाठ सामग्री रखता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a Text placeholder.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो पाठ सामग्री, एक ऊर्ध्वाधर दिशा में।

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a Text (Vertical) placeholder.

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक चित्र रखता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a Picture placeholder.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक चार्ट रखता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a Chart placeholder.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक तालिका रखता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a Table placeholder.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक SmartArt आकृति रखता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a SmartArt placeholder.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक मीडिया ऑब्जेक्ट रखता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with a Media placeholder.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

लेआउट स्लाइड में नई प्लेसहोल्डर आकार जोड़ता है जो एक ऑनलाइन छवि रखता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए प्लेसहोल्डर आकार का X समन्वय। |
| y | float | नए प्लेसहोल्डर आकार का Y समन्वय। |
| width | float | नए प्लेसहोल्डर आकार की चौड़ाई। |
| height | float | नए प्लेसहोल्डर आकार की ऊँचाई। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape) with an Online Image placeholder.