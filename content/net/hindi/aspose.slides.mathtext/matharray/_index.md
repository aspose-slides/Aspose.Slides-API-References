---
title: MathArray
second_title: Aspose.Sildes for .NET API संदर्भ
description: समीकरणों या किसी भी गणितीय वस्तु की लंबवत सरणी को निर्दिष्ट करता है
type: docs
weight: 8550
url: /hi/aspose.slides.mathtext/matharray/
---
## MathArray वर्ग

समीकरणों या किसी भी गणितीय वस्तु की लंबवत सरणी को निर्दिष्ट करता है

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | एक गणितीय सरणी बनाता है और निर्दिष्ट तत्वों को उसमें रखता है |
| [MathArray](matharray#constructor)(IMathElement) | एक गणितीय सरणी बनाता है और निर्दिष्ट तत्व को उसमें रखता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | सरणी के आइटम का सेट |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | सरणी की संरेखण को आसपास के पाठ के सापेक्ष निर्दिष्ट करता है। सरणी के बाहर का पाठ सरणी वस्तु के नीचे, ऊपर या केंद्र के साथ संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | अधिकतम वितरण। जब true हो, तो सरणी को सम्मिलित तत्व (पृष्ठ, कॉलम, सेल, आदि) की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | ऑब्जेक्ट वितरण। जब true हो, तो सरणी की सामग्री को सरणी वस्तु की अधिकतम चौड़ाई तक फैलाया जाता है। |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | सरणी की पंक्तियों के बीच स्पेसिंग। यह केवल तब उपयोग किया जाता है जब RowSpacingRule 3 पर सेट हो, अर्थात सटीक (एकाई बिंदु) या बहु (आधा-लाइन) हो। डिफ़ॉल्ट: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | सरणी तत्वों के बीच लंबवत स्पेसिंग का प्रकार। डिफ़ॉल्ट: SingleLineGap |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट चिह्न सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन लेता है, इस उदाहरण को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन लेता है, इस उदाहरण को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन लेता है, इस उदाहरण को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन लेता है, इस उदाहरण को तर्क और निर्दिष्ट अतिरिक्त तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन लेता है, इस उदाहरण को तर्क और निर्दिष्ट अतिरिक्त तर्क के रूप में उपयोग करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठकों में लपेटता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के रूप में लपेटता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | एक तर्क का फ़ंक्शन लेता है, इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | एक तर्क का फ़ंक्शन लेता है, इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करता है |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को निचले कर्ली ब्रैकेट का उपयोग करके समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को समूह में रखता है, समूहिंग अक्षर (जैसे निचला कर्ली ब्रैकेट या अन्य) का उपयोग करके |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए क्रम का गणितीय मूल निर्दिष्ट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए क्रम का गणितीय मूल निर्दिष्ट करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर उपस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या गणितीय पाठ के अन्य भागों के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड वस्तु (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर अनुक्रमण के रूप में कार्य कर सकती है, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित हो सकती है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में सम्मिलित करता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### देखें

* वर्ग [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathArray](../imatharray)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंब्ली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->