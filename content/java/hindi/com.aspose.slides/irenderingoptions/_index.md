---
title: IRenderingOptions
second_title: Aspose.Slides जावा API संदर्भ
description: एक प्रेज़ेंटेशन/स्लाइड को कैसे रेंडर किया जाता है, इसे नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/irenderingoptions/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IRenderingOptions extends ISaveOptions
```

एक प्रेज़ेंटेशन/स्लाइड को कैसे रेंडर किया जाता है, इसे नियंत्रित करने वाले विकल्प प्रदान करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      NotesCommentsLayoutingOptions notesCommentsLayoutingOptions = new NotesCommentsLayoutingOptions();
>      notesCommentsLayoutingOptions.setNotesPosition(NotesPositions.BottomTruncated);
>      renderingOpts.setSlidesLayoutOptions(notesCommentsLayoutingOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-Original.png"));
> 
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-ArialBlackDefault.png"));
> 
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-ArialNarrowDefault.png"));
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है जब प्रेज़ेंटेशन [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) निर्यात किया जाता है। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है जब प्रेज़ेंटेशन [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) निर्यात किया जाता है। |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink वस्तुओं के स्वरूप को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि टेक्स्ट लिगेचर के बिना रेंडर किया जाता है या नहीं। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि टेक्स्ट लिगेचर के बिना रेंडर किया जाता है या नहीं। |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है जब प्रेज़ेंटेशन [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) निर्यात किया जाता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      BufferedImage[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          ImageIO.write(handoutSlides[index], "PNG", new java.io.File("handout-" + index + ".png"));
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है जब प्रेज़ेंटेशन [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) निर्यात किया जाता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      BufferedImage[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          ImageIO.write(handoutSlides[index], "PNG", new java.io.File("handout-" + index + ".png"));
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

निर्यात किए गए दस्तावेज़ में Ink वस्तुओं के स्वरूप को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने-योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**रिटर्न:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि टेक्स्ट लिगेचर के बिना रेंडर किया जाता है या नहीं। जब true सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**  
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि टेक्स्ट लिगेचर के बिना रेंडर किया जाता है या नहीं। जब true सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |