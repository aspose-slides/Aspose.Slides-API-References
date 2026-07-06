---
title: MathArray
second_title: Aspose.Sildes for .NET API संदर्भ
description: समीकरणों या किसी भी गणितीय वस्तुओं की एक लंबवत एरे निर्दिष्ट करता है
type: docs
weight: 8550
url: /hi/aspose.slides.mathtext/matharray/
---
## MathArray क्लास

समीकरणों या किसी भी गणितीय वस्तुओं की एक लंबवत एरे निर्दिष्ट करता है

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | एक गणितीय एरे बनाता है और निर्दिष्ट तत्वों को उसमें रखता है |
| [MathArray](matharray#constructor)(IMathElement) | एक गणितीय एरे बनाता है और निर्दिष्ट तत्व को उसमें रखता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | एरे के आइटमों का सेट |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | एरे को आसपास के पाठ के सापेक्ष संरेखण निर्दिष्ट करता है। एरे के बाहर का पाठ एरे ऑब्जेक्ट के नीचे, ऊपर या मध्य में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Maximum Distribution जब true हो, एरे को सम्मिलित तत्व (पृष्ठ, कॉलम, सेल, आदि) की अधिकतम चौड़ाई तक विस्तारित किया जाता है। |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Object Distribution जब true हो, एरे की सामग्री को एरे ऑब्जेक्ट की अधिकतम चौड़ाई तक विस्तारित किया जाता है। |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | एरे की पंक्तियों के बीच का अंतर। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 Exactly पर सेट किया जाता है, जिसमें माप इकाई पॉइंट्स होती है या Multiple के मामले में माप इकाई अर्द्ध-लाइन होती है। डिफ़ॉल्ट: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | एरे तत्वों के बीच ऊर्ध्वाधर अंतराल का प्रकार। डिफ़ॉल्ट: SingleLineGap |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन लेता है और इस इंस्टेंस को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन लेता है और इस इंस्टेंस को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन लेता है और इस इंस्टेंस को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करता है और निर्दिष्ट अतिरिक्त तर्क को भी लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करता है और निर्दिष्ट अतिरिक्त तर्क को भी लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | गणितीय तत्व को कोष्ठकों में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में गणितीय तत्व को फ्रेमिंग के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | एक तर्क का फ़ंक्शन लेता है, इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | एक तर्क का फ़ंक्शन लेता है, इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करता है |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | संतान तत्व प्राप्त करें |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को नीचे की घुंघराली ब्रैकेट का उपयोग करके एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को समूहाकार अक्षर जैसे नीचे की घुंघराली ब्रैकेट या अन्य का उपयोग करके एक समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमा के बिना समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | दिए गए डिग्री की गणितीय मूल को निर्दिष्ट तर्क से निर्धारित करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | दिए गए डिग्री की गणितीय मूल को निर्दिष्ट तर्क से निर्धारित करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ पर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्युलेटर के रूप में काम कर सकता है, संरेखण बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित हो सकता है कि उसके भीतर लाइन ब्रेक न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत एरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### संबंधित देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathArray](../imatharray)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->