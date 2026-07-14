---
title: IRenderingOptions
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति/स्लाइड कैसे रेंडर किया जाता है।
type: docs
url: /hi/com.aspose.slides/irenderingoptions/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IRenderingOptions extends ISaveOptions
```

विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति/स्लाइड कैसे रेंडर किया जाता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      NotesCommentsLayoutingOptions notesCommentsLayoutingOptions = new NotesCommentsLayoutingOptions();
>      notesCommentsLayoutingOptions.setNotesPosition(NotesPositions.BottomTruncated);
>      renderingOpts.setSlidesLayoutOptions(notesCommentsLayoutingOptions);
>      FileOutputStream out = new FileOutputStream("pres-Original.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      FileOutputStream out = new FileOutputStream("pres-ArialBlackDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      FileOutputStream out = new FileOutputStream("pres-ArialNarrowDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्राप्त करता है या सेट करता है वह मोड जिसमें स्लाइड्स को पृष्ठ पर रखा जाता है जब प्रस्तुति को निर्यात किया जाता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्राप्त करता है या सेट करता है वह मोड जिसमें स्लाइड्स को पृष्ठ पर रखा जाता है जब प्रस्तुति को निर्यात किया जाता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | विकल्प प्रदान करता है जो निर्यात किए गए दस्तावेज़ में इंक ऑब्जेक्ट्स की दिखावट को नियंत्रित करते हैं। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | प्राप्त करता है या सेट करता है वह मान जो इंगित करता है कि पाठ बिना लिगेचर के रेंडर किया जाता है। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | प्राप्त करता है या सेट करता है वह मान जो इंगित करता है कि पाठ बिना लिगेचर के रेंडर किया जाता है। |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

प्राप्त करता है या सेट करता है वह मोड जिसमें स्लाइड्स को पृष्ठ पर रखा जाता है जब प्रस्तुति को निर्यात किया जाता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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
>      android.graphics.Bitmap[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          FileOutputStream out = new FileOutputStream("handout-" + index + ".png");
>          handoutSlides[index].compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

प्राप्त करता है या सेट करता है वह मोड जिसमें स्लाइड्स को पृष्ठ पर रखा जाता है जब प्रस्तुति को निर्यात किया जाता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)।

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
>      android.graphics.Bitmap[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          FileOutputStream out = new FileOutputStream("handout-" + index + ".png");
>          handoutSlides[index].compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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

विकल्प प्रदान करता है जो निर्यात किए गए दस्तावेज़ में इंक ऑब्जेक्ट्स की दिखावट को नियंत्रित करते हैं। केवल-पठन [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

प्राप्त करता है या सेट करता है वह मान जो इंगित करता है कि पाठ बिना लिगेचर के रेंडर किया जाता है। जब true पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर अक्षम हो जाते हैं। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।

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


**वापसी:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

प्राप्त करता है या सेट करता है वह मान जो इंगित करता है कि पाठ बिना लिगेचर के रेंडर किया जाता है। जब true पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर अक्षम हो जाते हैं। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।

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