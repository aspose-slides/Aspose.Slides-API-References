---
title: SpreadsheetOptions
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: विकल्पों का प्रतिनिधित्व करता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं।
type: docs
url: /hi/com.aspose.slides/spreadsheetoptions/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

स्प्रेडशीट व्यवहार को अतिरिक्त रूप से निर्दिष्ट करने के विकल्पों का प्रतिनिधित्व करता है।
## निर्माता

| Constructor | Description |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | नया उदाहरण आरंभ करता है [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) क्लास का। |
## विधियाँ

| Method | Description |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | डबल-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिये कुछ फ़ंक्शनों की गणना हेतु पसंदीदा संस्कृति जानकारी प्राप्त करता है या सेट करता है। |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | डबल-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिये कुछ फ़ंक्शनों की गणना हेतु पसंदीदा संस्कृति जानकारी प्राप्त करता है या सेट करता है। |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | यदि चार्ट का डेटा स्रोत बाहरी वर्कबुक है और उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनर्प्राप्त किया जाएगा। |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | यदि चार्ट का डेटा स्रोत बाहरी वर्कबुक है और उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनर्प्राप्त किया जाएगा। |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


नया उदाहरण आरंभ करता है [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) क्लास का।

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


डबल-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिये कुछ फ़ंक्शनों की गणना हेतु पसंदीदा संस्कृति जानकारी प्राप्त करता है या सेट करता है।

**वापसी:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


डबल-बाइट कैरेक्टर सेट (DBCS) का उपयोग करने वाली भाषाओं के लिये कुछ फ़ंक्शनों की गणना हेतु पसंदीदा संस्कृति जानकारी प्राप्त करता है या सेट करता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


यदि चार्ट का डेटा स्रोत बाहरी वर्कबुक है और उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनर्प्राप्त किया जाएगा।

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


**वापसी:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```


यदि चार्ट का डेटा स्रोत बाहरी वर्कबुक है और उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनर्प्राप्त किया जाएगा.

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