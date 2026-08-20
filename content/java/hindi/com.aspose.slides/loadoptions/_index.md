---
title: LoadOptions
second_title: Aspose.Slides for Java API संदर्भ
description: प्रेज़ेंटेशन लोड करते समय फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट जैसे अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
type: docs
url: /hi/com.aspose.slides/loadoptions/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)  
```
public class LoadOptions implements ILoadOptions
```

प्रेज़ेंटेशन लोड करते समय अतिरिक्त विकल्प (जैसे फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।

## कंस्ट्रक्टर्स

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | नई डिफ़ॉल्ट लोड विकल्प बनाता है। |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | नई लोड विकल्प बनाता है। |

## मेथड्स

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | लोड करने के लिए प्रेज़ेंटेशन का फ़ॉर्मेट प्राप्त या सेट करता है। |
| [setLoadFormat(int value)](#setLoadFormat-int-) | लोड करने के लिए प्रेज़ेंटेशन का फ़ॉर्मेट प्राप्त या सेट करता है। |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को प्राप्त या सेट करता है। |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को प्राप्त या सेट करता है। |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को प्राप्त या सेट करता है। |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को प्राप्त या सेट करता है। |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त या सेट करता है। |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त या सेट करता है। |
| [getPassword()](#getPassword--) | पासवर्ड प्राप्त या सेट करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड प्राप्त या सेट करता है। |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | यदि प्रेज़ेंटेशन फ़ाइल पासवर्ड-सुरक्षित है तो यह गुण मायने रखता है। |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | यदि प्रेज़ेंटेशन फ़ाइल पासवर्ड-सुरक्षित है तो यह गुण मायने रखता है। |
| [getWarningCallback()](#getWarningCallback--) | चेतावनियाँ प्राप्त करने और यह तय करने के लिए कि लोड प्रक्रिया जारी रहेगी या रोक दी जाएगी, ऐसे ऑब्जेक्ट को प्राप्त या सेट करता है। |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | चेतावनियाँ प्राप्त करने और यह तय करने के लिए कि लोड प्रक्रिया जारी रहेगी या रोक दी जाएगी, ऐसे ऑब्जेक्ट को प्राप्त या सेट करता है। |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | बाइनरी बड़े ऑब्जेक्ट (BLOB) हैंडलिंग व्यवहार को प्रबंधित करने के विकल्पों को दर्शाता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | बाइनरी बड़े ऑब्जेक्ट (BLOB) हैंडलिंग व्यवहार को प्रबंधित करने के विकल्पों को दर्शाता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट के स्रोत निर्दिष्ट करता है। |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट के स्रोत निर्दिष्ट करता है। |
| [getInterruptionToken()](#getInterruptionToken--) | बाधा अनुरोधों की निगरानी के लिए टोकन। |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | बाधा अनुरोधों की निगरानी के लिए टोकन। |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | बाहरी संसाधनों के लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को प्राप्त या सेट करता है। |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | बाहरी संसाधनों के लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को प्राप्त या सेट करता है। |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | स्प्रेडशीट्स के विकल्प प्राप्त करता है। |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | स्प्रेडशीट्स के विकल्प प्राप्त करता है। |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | प्रेज़ेंटेशन पाठ की डिफ़ॉल्ट भाषा को प्राप्त या सेट करता है। |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | प्रेज़ेंटेशन पाठ की डिफ़ॉल्ट भाषा को प्राप्त या सेट करता है। |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | यदि लोडिंग के दौरान Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट को हटाता है, तो निर्धारित करता है। |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | यदि लोडिंग के दौरान Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट को हटाता है, तो निर्धारित करता है। |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

नया डिफ़ॉल्ट लोड विकल्प बनाता है।

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

नया लोड विकल्प बनाता है।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| loadFormat | int | लोड करने के लिए प्रेज़ेंटेशन का फ़ॉर्मेट। |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

लोड करने के लिए प्रेज़ेंटेशन का फ़ॉर्मेट प्राप्त या सेट करता है। पढ़ें/लिखें [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**  
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

लोड करने के लिए प्रेज़ेंटेशन का फ़ॉर्मेट प्राप्त या सेट करता है। पढ़ें/लिखें [LoadFormat](../../com.aspose.slides/loadformat).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को प्राप्त या सेट करता है। पढ़ें/लिखें String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट नियमित और एशियाई फ़ॉन्ट निर्धारित करें
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // प्रेज़ेंटेशन लोड करें
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // स्लाइड थंबनेल बनाएं
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // PDF बनाएं
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS बनाएं
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**Returns:**  
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को प्राप्त या सेट करता है। पढ़ें/लिखें String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट नियमित और एशियाई फ़ॉन्ट निर्धारित करें
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // प्रेज़ेंटेशन लोड करें
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // स्लाइड थंबनेल बनाएं
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // PDF बनाएं
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS बनाएं
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को प्राप्त या सेट करता है। पढ़ें/लिखें String.

**Returns:**  
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को प्राप्त या सेट करता है। पढ़ें/लिखें String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त या सेट करता है। पढ़ें/लिखें String.

**Returns:**  
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त या सेट करता है। पढ़ें/लिखें String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

पासवर्ड प्राप्त या सेट करता है। पढ़ें/लिखें String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // डिक्रिप्टेड प्रेज़ेंटेशन के साथ काम करें
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Value: पासवर्ड।

**Returns:**  
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

पासवर्ड प्राप्त या सेट करता है। पढ़ें/लिखें String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // डिक्रिप्टेड प्रेज़ेंटेशन के साथ काम करें
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Value: पासवर्ड।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

यदि प्रेज़ेंटेशन फ़ाइल पासवर्ड-सुरक्षित है तो यह गुण मायने रखता है। true का मान मतलब केवल एन्क्रिप्टेड फ़ाइल से दस्तावेज़ के गुण लोड किए जाएंगे और पासवर्ड को अनदेखा किया जाएगा। false का मान मतलब पूरे एन्क्रिप्टेड प्रेज़ेंटेशन को सही पासवर्ड के साथ लोड किया जाएगा। यदि प्रेज़ेंटेशन एन्क्रिप्टेड नहीं है तो यह मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और मान true है, तो दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद उत्पन्न होगा। पढ़ें/लिखें boolean.

**Returns:**  
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

यदि प्रेज़ेंटेशन फ़ाइल पासवर्ड-सुरक्षित है तो यह गुण मायने रखता है। true का मान मतलब केवल एन्क्रिप्टेड फ़ाइल से दस्तावेज़ के गुण लोड किए जाएंगे और पासवर्ड को अनदेखा किया जाएगा। false का मान मतलब पूरे एन्क्रिप्टेड प्रेज़ेंटेशन को सही पासवर्ड के साथ लोड किया जाएगा। यदि प्रेज़ेंटेशन एन्क्रिप्टेड नहीं है तो यह मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और मान true है, तो दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद उत्पन्न होगा। पढ़ें/लिखें boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

लोड प्रक्रिया जारी रहेगी या बंद की जाएगी, यह तय करने के लिए चेतावनियाँ प्राप्त करने वाले ऑब्जेक्ट को प्राप्त या सेट करता है। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returns:**  
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

लोड प्रक्रिया जारी रहेगी या बंद की जाएगी, यह तय करने के लिए चेतावनियाँ प्राप्त करने वाले ऑब्जेक्ट को प्राप्त या सेट करता है। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

बाइनरी बड़े ऑब्जेक्ट (BLOB) हैंडलिंग व्यवहार को प्रबंधित करने के विकल्पों को दर्शाता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। ये विकल्प विशेष पर्यावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/मेमोरी खपत अनुपात सेट करने के लिए हैं।

--------------------

एक बाइनरी बड़ा ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक इकाई के रूप में संग्रहीत होता है—उदाहरण के लिये BLOB ऑडियो, वीडियो या प्रेज़ेंटेशन स्वयं हो सकता है।

**Returns:**  
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

बाइनरी बड़े ऑब्जेक्ट (BLOB) हैंडलिंग व्यवहार को प्रबंधित करने के विकल्पों को दर्शाता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। ये विकल्प विशेष पर्यावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/मेमोरी खपत अनुपात सेट करने के लिए हैं।

--------------------

एक बाइनरी बड़ा ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक इकाई के रूप में संग्रहीत होता है—उदाहरण के लिये BLOB ऑडियो, वीडियो या प्रेज़ेंटेशन स्वयं हो सकता है।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट के स्रोत को निर्दिष्ट करता है। ये फ़ॉन्ट प्रेज़ेंटेशन के पूरे जीवनकाल में उपलब्ध होते हैं और अन्य प्रेज़ेंटेशन के साथ साझा नहीं होते।

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //प्रेज़ेंटेशन के साथ काम करें
>  //CustomFont1, CustomFont2 के साथ-साथ assets\fonts और global\fonts फ़ोल्डरों तथा उनके सबफ़ोल्डरों से फ़ॉन्ट प्रेज़ेंटेशन के लिए उपलब्ध हैं
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returns:**  
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट के स्रोत को निर्दिष्ट करता है। ये फ़ॉन्ट प्रेज़ेंटेशन के पूरे जीवनकाल में उपलब्ध होते हैं और अन्य प्रेज़ेंटेशन के साथ साझा नहीं होते।

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //प्रेज़ेंटेशन के साथ काम करें
>  //CustomFont1, CustomFont2 के साथ-साथ assets\fonts और global\fonts फ़ोल्डरों तथा उनके सबफ़ोल्डरों से फ़ॉन्ट प्रेज़ेंटेशन के लिए उपलब्ध हैं
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

बाधा अनुरोधों की निगरानी के लिए टोकन।

--------------------

यह टोकन पूरे [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस के जीवनकाल को प्रबंधित करता है। कोई भी लंबी-चलाने वाली प्रक्रिया, जैसे प्रेज़ेंटेशन का लोड या सहेजना, [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) मेथड को [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) पर कॉल करके बाधित की जाएगी।

**Returns:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

बाधा अनुरोधों की निगरानी के लिए टोकन।

--------------------

यह टोकन पूरे [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस के जीवनकाल को प्रबंधित करता है। कोई भी लंबी-चलाने वाली प्रक्रिया, जैसे प्रेज़ेंटेशन का लोड या सहेजना, [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) मेथड को [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) पर कॉल करके बाधित की जाएगी।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

बाहरी संसाधनों के लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को प्राप्त या सेट करता है। पढ़ें/लिखें [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Returns:**  
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

बाहरी संसाधनों के लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को प्राप्त या सेट करता है। पढ़ें/लिखें [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

स्प्रेडशीट्स के विकल्प प्राप्त करता है। उदाहरण के लिये, ये विकल्प चार्ट की फ़ॉर्मूला गणना को प्रभावित करते हैं।

**Returns:**  
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

स्प्रेडशीट्स के विकल्प प्राप्त करता है। उदाहरण के लिये, ये विकल्प चार्ट की फ़ॉर्मूला गणना को प्रभावित करते हैं।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

प्रेज़ेंटेशन पाठ की डिफ़ॉल्ट भाषा को प्राप्त या सेट करता है। पढ़ें/लिखें String.

--------------------

> ```
> Example:
>   
>  // Use load options to define the default text culture
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Add new rectangle shape with text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Check the first portion language
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**  
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

प्रेज़ेंटेशन पाठ की डिफ़ॉल्ट भाषा को प्राप्त या सेट करता है। पढ़ें/लिखें String.

--------------------

> ```
> Example:
>   
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट टेक्स्ट कल्चर निर्धारित करें
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // टेक्स्ट के साथ नया आयताकार आकार जोड़ें
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // पहले भाग की भाषा जाँचें
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

लोडिंग के दौरान Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट को हटाएगा या नहीं, यह निर्धारित करता है।

एम्बेडेड बाइनरी ऑब्जेक्ट के प्रकार:

पढ़ें/लिखें boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफ़ॉल्ट **false** है।

**Returns:**  
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

लोडिंग के दौरान Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट को हटाएगा या नहीं, यह निर्धारित करता है।

एम्बेडेड बाइनरी ऑब्जेक्ट के प्रकार:

पढ़ें/लिखें boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

डिफ़ॉल्ट **false** है।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |