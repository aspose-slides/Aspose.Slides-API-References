---
title: IXamlOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: वे विकल्प जो नियंत्रित करते हैं कि XAML दस्तावेज़ कैसे सहेजा जाता है।
type: docs
url: /hi/com.aspose.slides/ixamloptions/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

XAML दस्तावेज़ को सहेजने के तरीके को नियंत्रित करने वाले विकल्प।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## विधियां

| विधि | विवरण |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। |
| [getOutputSaver()](#getOutputSaver--) | IOutputSaver इंटरफ़ेस का एक कार्यान्वयन दर्शाता है। |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | IOutputSaver इंटरफ़ेस का एक कार्यान्वयन दर्शाता है। |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```


IOutputSaver इंटरफ़ेस का एक कार्यान्वयन दर्शाता है।

**रिटर्न:**  
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


IOutputSaver इंटरफ़ेस का एक कार्यान्वयन दर्शाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |