---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: ऐसे विकल्पों का प्रतिनिधित्व करता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं।
type: docs
url: /hi/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

ऐसे विकल्पों का प्रतिनिधित्व करता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | डबल-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिये कुछ फ़ंक्शनों की गणना हेतु वांछित संस्कृति जानकारी प्राप्त करता है या सेट करता है। |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | डबल-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिये कुछ फ़ंक्शनों की गणना हेतु वांछित संस्कृति जानकारी प्राप्त करता है या सेट करता है। |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | यदि चार्ट के लिए डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनः प्राप्त किया जाएगा। |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | यदि चार्ट के लिए डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनः प्राप्त किया जाएगा। |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

डबल-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिये कुछ फ़ंक्शनों की गणना हेतु वांछित संस्कृति जानकारी प्राप्त करता है या सेट करता है।

**रिटर्न:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

डबल-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिये कुछ फ़ंक्शनों की गणना हेतु वांछित संस्कृति जानकारी प्राप्त करता है या सेट करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Locale |  |
### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

यदि चार्ट के लिए डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनः प्राप्त किया जाएगा।

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**रिटर्न:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

यदि चार्ट के लिए डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनः प्राप्त किया जाएगा।

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |