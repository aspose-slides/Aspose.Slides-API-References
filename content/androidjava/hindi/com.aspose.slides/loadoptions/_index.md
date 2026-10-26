---
title: LoadOptions
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: प्रस्तुति लोड करते समय फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट जैसे अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
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

प्रस्तुति लोड करने के दौरान अतिरिक्त विकल्प (जैसे फॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | नया डिफ़ॉल्ट लोड विकल्प बनाता है। |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | नया लोड विकल्प बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | लोड करने के लिए प्रस्तुति के फॉर्मेट को प्राप्त करता या सेट करता है। |
| [setLoadFormat(int value)](#setLoadFormat-int-) | लोड करने के लिए प्रस्तुति के फॉर्मेट को प्राप्त करता या सेट करता है। |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Regular फ़ॉन्ट को प्राप्त करता या सेट करता है। |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Regular फ़ॉन्ट को प्राप्त करता या सेट करता है। |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Symbol फ़ॉन्ट को प्राप्त करता या सेट करता है। |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Symbol फ़ॉन्ट को प्राप्त करता या सेट करता है। |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Asian फ़ॉन्ट को प्राप्त करता या सेट करता है। |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Asian फ़ॉन्ट को प्राप्त करता या सेट करता है। |
| [getPassword()](#getPassword--) | पासवर्ड को प्राप्त करता या सेट करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड को प्राप्त करता या सेट करता है। |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | यह गुण तब समझ में आता है जब प्रस्तुति फ़ाइल पासवर्ड से सुरक्षित हो। |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | यह गुण तब समझ में आता है जब प्रस्तुति फ़ाइल पासवर्ड से सुरक्षित हो। |
| [getWarningCallback()](#getWarningCallback--) | चेतावनियों को प्राप्त करने वाला ऑब्जेक्ट को प्राप्त करता या सेट करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | चेतावनियों को प्राप्त करने वाला ऑब्जेक्ट को प्राप्त करता या सेट करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Binary Large Objects (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के विकल्पों का प्रतिनिधित्व करता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Binary Large Objects (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के विकल्पों का प्रतिनिधित्व करता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। |
| [getInterruptionToken()](#getInterruptionToken--) | विच्छेदन अनुरोधों की निगरानी के लिए टोकन। |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | विच्छेदन अनुरोधों की निगरानी के लिए टोकन। |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | बाहरी संसाधनों के लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को प्राप्त करता या सेट करता है। |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | बाहरी संसाधनों के लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को प्राप्त करता या सेट करता है। |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | स्प्रेडशीट्स के विकल्प प्राप्त करता है। |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | स्प्रेडशीट्स के विकल्प प्राप्त करता है। |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | प्रस्तुति टेक्स्ट के लिए डिफ़ॉल्ट भाषा को प्राप्त करता या सेट करता है। |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | प्रस्तुति टेक्स्ट के लिए डिफ़ॉल्ट भाषा को प्राप्त करता या सेट करता है। |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | निर्धारित करता है कि Aspose.Slides लोडिंग के दौरान सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं। |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | निर्धारित करता है कि Aspose.Slides लोडिंग के दौरान सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं। |
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| loadFormat | int | लोड करने के लिए प्रस्तुति का फॉर्मेट। |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


लोड करने के लिए प्रस्तुति का फॉर्मेट प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [LoadFormat](../../com.aspose.slides/loadformat)।

**रिटर्न:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```


लोड करने के लिए प्रस्तुति का फॉर्मेट प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [LoadFormat](../../com.aspose.slides/loadformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Regular फ़ॉन्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट रेग्युलर और एशियन फ़ॉन्ट्स परिभाषित करें
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // प्रस्तुति लोड करें
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // स्लाइड थंबनेल उत्पन्न करें
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // PDF उत्पन्न करें
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS उत्पन्न करें
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Regular फ़ॉन्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट रेग्युलर और एशियन फ़ॉन्ट्स को परिभाषित करें
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // प्रस्तुति लोड करें
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // स्लाइड थंबनेल उत्पन्न करें
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // PDF उत्पन्न करें
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS उत्पन्न करें
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```


स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Symbol फ़ॉन्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```


स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Symbol फ़ॉन्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```


स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Asian फ़ॉन्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```


स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले Asian फ़ॉन्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String।

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // डिक्रिप्टेड प्रस्तुति के साथ काम करें
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


मान: पासवर्ड।

**रिटर्न:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String।

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // डिक्रिप्टेड प्रस्तुति के साथ काम करें
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


मान: पासवर्ड।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```


यह गुण तब समझ में आता है जब प्रस्तुति फ़ाइल पासवर्ड से सुरक्षित हो। true मान का अर्थ है कि केवल दस्तावेज़ गुणों को एन्क्रिप्टेड प्रस्तुति फ़ाइल से लोड करना चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए। false मान का अर्थ है कि पूरे एन्क्रिप्टेड प्रस्तुति को सही पासवर्ड के उपयोग से लोड किया जाना चाहिए। यदि प्रस्तुति एन्क्रिप्टेड नहीं है तो इस गुण का मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और गुण का मान true है तो दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद उत्पन्न होगा। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```


यह गुण तब समझ में आता है जब प्रस्तुति फ़ाइल पासवर्ड से सुरक्षित हो। true मान का अर्थ है कि केवल दस्तावेज़ गुणों को एन्क्रिप्टेड प्रस्तुति फ़ाइल से लोड करना चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए। false मान का अर्थ है कि पूरे एन्क्रिप्टेड प्रस्तुति को सही पासवर्ड के उपयोग से लोड किया जाना चाहिए। यदि प्रस्तुति एन्क्रिप्टेड नहीं है तो इस गुण का मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और गुण का मान true है तो दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद उत्पन्न होगा। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


चेतावनियों को प्राप्त करने वाला ऑब्जेक्ट को प्राप्त करता या सेट करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। पढ़ने/लिखने योग्य [IWarningCallback](../../com.aspose.slides/iwarningcallback)।

**रिटर्न:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


चेतावनियों को प्राप्त करने वाला ऑब्जेक्ट को प्राप्त करता या सेट करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। पढ़ने/लिखने योग्य [IWarningCallback](../../com.aspose.slides/iwarningcallback)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```


Binary Large Objects (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के विकल्पों को दर्शाता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। ये विकल्प विशेष वातावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/स्मृति उपयोग अनुपात को सेट करने के लिए अभिप्रेत हैं।

--------------------

Binary Large Object (BLOB) एक बाइनरी डेटा है जो एक इकाई के रूप में संग्रहीत होता है - अर्थात् BLOB ऑडियो, वीडियो या स्वयं प्रस्तुति हो सकता है।

**रिटर्न:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```


Binary Large Objects (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के विकल्पों को दर्शाता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। ये विकल्प विशेष वातावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/स्मृति उपयोग अनुपात को सेट करने के लिए अभिप्रेत हैं।

--------------------

Binary Large Object (BLOB) एक बाइनरी डेटा है जो एक इकाई के रूप में संग्रहीत होता है - अर्थात् BLOB ऑडियो, वीडियो या स्वयं प्रस्तुति हो सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```


प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रस्तुति की जीवनकाल भर उपलब्ध होते हैं और अन्य प्रस्तुतियों के साथ साझा नहीं होते।

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```


प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रस्तुति की जीवनकाल भर उपलब्ध होते हैं और अन्य प्रस्तुतियों के साथ साझा नहीं होते।

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```


विच्छेदन अनुरोधों की निगरानी के लिए टोकन।

--------------------

यह टोकन पूरे [IPresentation](../../com.aspose.slides/ipresentation) उदाहरण के जीवनकाल को प्रबंधित करता है। कोई भी लंबा-चलाने वाला कार्य, जैसे प्रस्तुति को लोड या सहेजना, [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) मेथड को कॉल करके [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) द्वारा बाधित किया जाएगा।

**रिटर्न:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```


विच्छेदन अनुरोधों की निगरानी के लिए टोकन।

--------------------

यह टोकन पूरे [IPresentation](../../com.aspose.slides/ipresentation) उदाहरण के जीवनकाल को प्रबंधित करता है। कोई भी लंबा-चलाने वाला कार्य, जैसे प्रस्तुति को लोड या सहेजना, [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) मेथड को कॉल करके [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) द्वारा बाधित किया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```


बाहरी संसाधनों के लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)।

**रिटर्न:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```


बाहरी संसाधनों के लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```


स्प्रेडशीट्स के विकल्प प्राप्त करता है। उदाहरण के लिए, ये विकल्प चार्ट के फ़ॉर्मूला गणना को प्रभावित करते हैं।

**रिटर्न:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```


स्प्रेडशीट्स के विकल्प प्राप्त करता है। उदाहरण के लिए, ये विकल्प चार्ट के फ़ॉर्मूला गणना को प्रभावित करते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```


प्रस्तुति टेक्स्ट के लिए डिफ़ॉल्ट भाषा को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String।

--------------------

> ```
> Example:
>   
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट टेक्स्ट कल्चर परिभाषित करें
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // नए आयताकार आकार को टेक्स्ट के साथ जोड़ें
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // पहले भाग की भाषा जाँचें
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```


प्रस्तुति टेक्स्ट के लिए डिफ़ॉल्ट भाषा को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String।

--------------------

> ```
> Example:
>   
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट टेक्स्ट कल्चर को परिभाषित करें
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


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```


Aspose.Slides लोडिंग के दौरान सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं, यह निर्धारित करता है।

एंबेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:

पढ़ने/लिखने योग्य boolean .

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

**रिटर्न:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```


Aspose.Slides लोडिंग के दौरान सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं, यह निर्धारित करता है।

एंबेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:

पढ़ने/लिखने योग्य boolean .

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |