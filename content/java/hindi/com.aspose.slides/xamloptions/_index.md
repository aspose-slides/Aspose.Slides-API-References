---
title: XamlOptions
second_title: Aspose.Slides for Java API संदर्भ
description: विकल्प जो नियंत्रित करते हैं कि XAML दस्तावेज़ कैसे सहेजा जाता है।
type: docs
url: /hi/com.aspose.slides/xamloptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी कार्यान्वित इंटरफेस:**  
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)  
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

XAML दस्तावेज़ को सहेजने के तरीकों को नियंत्रित करने वाले विकल्प।

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
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | XamlOptions इंस्टेंस बनाता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | निर्धारित करता है कि छिपी स्लाइडें निर्यात की जाएँगी या नहीं। |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | निर्धारित करता है कि छिपी स्लाइडें निर्यात की जाएँगी या नहीं। |
| [getOutputSaver()](#getOutputSaver--) | IOutputSaver इंटरफ़ेस का कार्यान्वयन दर्शाता है। |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | IOutputSaver इंटरफ़ेस का कार्यान्वयन दर्शाता है। |

### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

XamlOptions इंस्टेंस बनाता है।

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

निर्धारित करता है कि छिपी स्लाइडें निर्यात की जाएँगी या नहीं।

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

**वापसी:**  
boolean

### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

निर्धारित करता है कि छिपी स्लाइडें निर्यात की जाएँगी या नहीं।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```

IOutputSaver इंटरफ़ेस का कार्यान्वयन दर्शाता है।

**वापसी:**  
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)

### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

IOutputSaver इंटरफ़ेस का कार्यान्वयन दर्शाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |