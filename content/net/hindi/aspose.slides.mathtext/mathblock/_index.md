---
title: MathBlock
second_title: Aspose.Sildes for .NET API संदर्भ
description: MathParagraph के भीतर सम्मिलित गणितीय टेक्स्ट का एक उदाहरण निर्दिष्ट करता है और अपनी स्वयं की पंक्ति पर शुरू होता है। सभी गणितीय क्षेत्रों को, जिसमें समीकरण, अभिव्यक्तियों, समीकरणों या अभिव्यक्तियों की सरणियों और सूत्र शामिल हैं, गणितीय ब्लॉक द्वारा प्रतिनिधित्व किया जाता है।
type: docs
weight: 8590
url: /hi/aspose.slides.mathtext/mathblock/
---
## MathBlock वर्ग

एक गणितीय पाठ का उदाहरण निर्दिष्ट करता है जो MathParagraph के भीतर शामिल है और अपनी खुद की पंक्ति पर शुरू होता है। सभी गणितीय क्षेत्र, जिसमें समीकरण, अभिव्यक्तियाँ, समीकरणों या अभिव्यक्तियों की सरणियाँ, और सूत्र शामिल हैं, को MathBlock द्वारा दर्शाया जाता है।

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## कंस्ट्रक्टर

| नाम | विवरण |
| --- | --- |
| [MathBlock](mathblock#constructor)() | MathBlock वर्ग की नई उदाहरण को प्रारंभ करता है। |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | एक नया MathBlock बनाता है और निर्दिष्ट तत्वों को इसमें रखता है |
| [MathBlock](mathblock#constructor_1)(IMathElement) | एक नया MathBlock बनाता है और निर्दिष्ट तत्व को इसमें रखता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | संग्रह में वास्तव में शामिल चाइल्ड गणितीय तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य Int32। |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | false लौटाता है क्योंकि चाइल्ड तत्वों का संग्रह संशोधित किया जा सकता है। |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | निर्दिष्ट सूचकांक पर IMathElement प्राप्त करता है या सेट करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के शीर्ष पर एक स्वर संकेत (एक अक्षर) सेट करता है |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | संग्रह के अंत में एक गणितीय तत्व जोड़ता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करके लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करके लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में उपयोग करके लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके लेता है |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | संग्रह से सभी तत्वों को हटाता है |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | निर्धारित करता है कि क्या संग्रह में कोई विशिष्ट मान मौजूद है |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | निर्दिष्ट एरे में कॉपी करता है |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | चाइल्ड तत्वों को विभाजक अक्षर (कोष्ठकों के बिना) से सीमित करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर के साथ एक भाग बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भाग बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का एक भाग इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार का एक भाग इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठकों में बंद करता है |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में बंद करता है |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | इस ब्लॉक के चाइल्ड तत्वों को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य में फ्रेमिंग करता है और विभाजक अक्षर से सीमित करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | चाइल्ड तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे की कर्ली ब्रैकट का उपयोग करके इस तत्व को समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे की कर्ली ब्रैकट या अन्य जैसे समूहित करने वाले अक्षर का उपयोग करके इस तत्व को समूह में रखता है |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | संग्रह में किसी विशिष्ट गणितीय तत्व का सूचकांक निर्धारित करता है |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | निर्दिष्ट सूचकांक पर एक MathElement को संग्रह में डालता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | एक गणितीय तत्व को इस गणितीय ब्लॉक के साथ जोड़ता है |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | एक गणितीय पाठ को इस गणितीय ब्लॉक के साथ जोड़ता है |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | एक अन्य गणितीय ब्लॉक को इस ब्लॉक के साथ जोड़ता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल निर्धारित करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल निर्धारित करता है |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | संग्रह से विशिष्ट वस्तु की पहली घटना को हटाता है |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपर्सक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपर्सक्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक नॉन-विजुअल बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एमुलेटर के रूप में कार्य कर सकता है, चाहे उसमें संरेखण बिंदु हो या न हो, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | चाइल्ड तत्वों को एक लंबवत एरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के निचले हिस्से पर एक बार सेट करता है |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | इस [`MathBlock`](../mathblock) की सामग्री को MathML के रूप में सहेजता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### देखें भी

* वर्ग [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathBlock](../imathblock)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंब्ली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->