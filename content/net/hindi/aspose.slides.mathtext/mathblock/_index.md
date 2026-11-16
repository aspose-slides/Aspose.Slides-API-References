---
title: MathBlock
second_title: Aspose.Sildes for .NET API संदर्भ
description: MathParagraph के भीतर मौजूद गणितीय पाठ का एक उदाहरण निर्दिष्ट करता है जो अपनी स्वयं की पंक्ति से शुरू होता है। सभी गणितीय क्षेत्रों, जिसमें समीकरण, अभिव्यक्तियाँ, समीकरणों या अभिव्यक्तियों की श्रृंखलाएँ और सूत्र शामिल हैं, को math block द्वारा प्रतिनिधित्व किया जाता है।
type: docs
weight: 8610
url: /hi/aspose.slides.mathtext/mathblock/
---
## MathBlock क्लास

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathBlock](mathblock#constructor)() | MathBlock क्लास का नया उदाहरण प्रारंभ करता है। |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्वों को उसमें रखता है |
| [MathBlock](mathblock#constructor_1)(IMathElement) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व को उसमें रखता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | संग्रह में वास्तव में मौजूद child math elements की संख्या प्राप्त करता है। केवल-पढ़ने योग्य Int32। |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | false लौटाता है क्योंकि child elements संग्रह को संशोधित किया जा सकता है। |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | निर्दिष्ट सूचकांक पर IMathElement को प्राप्त या सेट करता है। |

## विधियों

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के ऊपर एक उच्चारण चिह्न (एक अक्षर) सेट करता है |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | संग्रह के अंत में एक math तत्व जोड़ता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और निर्दिष्ट अतिरिक्त तर्क के साथ लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को इस उदाहरण को तर्क के रूप में लेकर और निर्दिष्ट अतिरिक्त तर्क के साथ लेता है |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | संग्रह से सभी तत्वों को हटाता है। |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | निर्धारित करता है कि संग्रह में कोई विशिष्ट मान मौजूद है या नहीं। |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | निर्दिष्ट सरणी में कॉपी करता है। |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | ब्रैकेट के बिना विभाजक अक्षर से child तत्वों को सीमांकित करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक तथा निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक तथा निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न को इस अंशांक तथा निर्दिष्ट हर के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न को इस अंशांक तथा निर्दिष्ट हर के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक math तत्व को कोष्ठक में बंद करता है |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | इस ब्लॉक के child तत्वों को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य) में फ्रेमिंग के रूप में बंद करता है |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | इस ब्लॉक के child तत्वों को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य) में फ्रेमिंग कर और विभाजक अक्षर से सीमांकित करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | child तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | समूह बनाने के लिए समूह करने वाला अक्षर (जैसे नीचे की कर्ली ब्रैकेट या अन्य) का उपयोग करके इस तत्व को रखता है |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | संग्रह में किसी विशिष्ट math तत्व का सूचकांक निर्धारित करता है। |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | निर्दिष्ट सूचकांक पर संग्रह में एक MathElement डालता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | बिना सीमाओं के समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | एक गणितीय तत्व को इस गणितीय ब्लॉक के साथ जोड़ता है |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | एक गणितीय पाठ को इस गणितीय ब्लॉक के साथ जोड़ता है |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | इस ब्लॉक के साथ एक और गणितीय ब्लॉक को जोड़ता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए क्रमांक की गणितीय मूल निर्धारित करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए क्रमांक की गणितीय मूल निर्धारित करता है |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | संग्रह से किसी विशेष वस्तु की पहली उपस्थिति को हटाता है |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | नीचे लिखा (subscript) बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | नीचे लिखा (subscript) बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ नीचे लिखा और ऊपर लिखा बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ नीचे लिखा और ऊपर लिखा बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ नीचे लिखा और ऊपर लिखा बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ नीचे लिखा और ऊपर लिखा बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ऊपर लिखा (superscript) बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ऊपर लिखा (superscript) बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपर की सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपर की सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) सन्निवेशन बिंदु के साथ या बिना, ऑपरेटर इम्यूलेटर, लाइन-ब्रेक बिंदु या ऐसी समूहबद्धता प्रदान कर सकता है जिससे लाइन-ब्रेक की अनुमति न हो। |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | child तत्वों को एक लंबवत क्रम में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | इस [`MathBlock`](../mathblock) की सामग्री को MathML के रूप में सहेजता है |

### उदाहरण

Example:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathBlock](../imathblock)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंब्ली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->