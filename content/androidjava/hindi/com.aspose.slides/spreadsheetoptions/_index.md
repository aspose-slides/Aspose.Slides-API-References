---
title: SpreadsheetOptions
second_title: Aspose.Slides for Android के लिए Java API रेफरेंस
description: ऐसे विकल्पों का प्रतिनिधित्व करता है जिन्हें अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किया जा सकता है।
type: docs
url: /hi/com.aspose.slides/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

ऐसे विकल्पों का प्रतिनिधित्व करता है जिन्हें अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किया जा सकता है।
## कंस्ट्रक्टर्स

| Constructor | Description |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| Method | Description |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | कुछ फ़ंक्शनों की गणना के लिए पसंदीदा संस्कृति जानकारी प्राप्त करता है या सेट करता है, जो द्वि-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिए है। |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | कुछ फ़ंक्शनों की गणना के लिए पसंदीदा संस्कृति जानकारी प्राप्त करता है या सेट करता है, जो द्वि-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिए है। |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | यदि चार्ट का डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनः प्राप्त किया जाएगा। |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | यदि चार्ट का डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनः प्राप्त किया जाएगा। |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


[SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


कुछ फ़ंक्शनों की गणना के लिए पसंदीदा संस्कृति जानकारी प्राप्त करता है या सेट करता है, जो द्वि-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिए है।

**रिटर्न:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


कुछ फ़ंक्शनों की गणना के लिए पसंदीदा संस्कृति जानकारी प्राप्त करता है या सेट करता है, जो द्वि-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिए है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


यदि चार्ट का डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनः प्राप्त किया जाएगा।

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```


यदि चार्ट का डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनः प्राप्त किया जाएगा।

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |