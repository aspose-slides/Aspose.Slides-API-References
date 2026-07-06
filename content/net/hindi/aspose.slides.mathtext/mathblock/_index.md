---
title: MathBlock
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक MathParagraph के भीतर समाहित गणितीय पाठ का एक उदाहरण निर्दिष्ट करता है और अपनी स्वयं की पंक्ति पर शुरू होता है। सभी गणितीय क्षेत्रों, जिसमें समीकरण, अभिव्यक्तियाँ, समीकरणों या अभिव्यक्तियों के ऐरे और सूत्र शामिल हैं, को गणित ब्लॉक द्वारा प्रतिनिधित्व किया जाता है।
type: docs
weight: 8590
url: /hi/aspose.slides.mathtext/mathblock/
---
## MathBlock कक्षा

एक गणितीय पाठ का उदाहरण निर्दिष्ट करता है जो MathParagraph के भीतर स्थित है और अपनी खुद की लाइन पर शुरू होता है। सभी गणितीय ज़ोन, जिसमें समीकरण, अभिव्यक्तियाँ, समीकरणों या अभिव्यक्तियों के ऐरे, और सूत्र शामिल हैं, गणित ब्लॉक द्वारा प्रतिनिधित्व किए जाते हैं।

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathBlock](mathblock#constructor)() | MathBlock कक्षा का एक नया उदाहरण प्रारंभ करता है। |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्वों को उसमें रखता है |
| [MathBlock](mathblock#constructor_1)(IMathElement) | एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व को उसमें रखता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | कलेक्शन में वास्तव में शामिल बच्चा गणित तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य Int32। |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | false लौटाता है क्योंकि बच्चा तत्वों का कलेक्शन संशोधित किया जा सकता है। |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | निर्दिष्ट इंडेक्स पर IMathElement प्राप्त करता या सेट करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के ऊपर एक एक्सेंट चिह्न (एक अक्षर) सेट करता है |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | संग्रह के अंत में एक गणितीय तत्व जोड़ता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क प्रदान करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क प्रदान करता है |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | सभी तत्वों को संग्रह से हटाता है। |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | जाँचता है कि संग्रह में विशिष्ट मान मौजूद है या नहीं। |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | निर्दिष्ट ऐरे में कॉपी करता है। |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | ब्रैकेट के बिना विभाजक अक्षर के साथ बच्चा तत्वों को अलग करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक (numerator) और निर्दिष्ट हर (denominator) के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है जिसमें यह अंशांक और निर्दिष्ट हर होते हैं |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है जिसमें यह अंशांक और निर्दिष्ट हर होते हैं |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठकों में enclosed करता है |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | इस ब्लॉक के बच्चा तत्वों को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य) में envelop करता है |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | इस ब्लॉक के बच्चा तत्वों को निर्दिष्ट अक्षरों में enkapsulate करता है और एक विभाजक अक्षर के साथ अलग करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | बच्चे तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को नीचे की घुंघराले कोष्ठक का उपयोग करके एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को निर्दिष्ट ग्रुपिंग अक्षर (जैसे नीचे की घुंघराले कोष्ठक) का उपयोग करके समूहित करता है |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | संग्रह में विशिष्ट गणितीय तत्व का सूचकांक निर्धारित करता है। |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | निर्दिष्ट इंडेक्स पर MathElement को संग्रह में सम्मिलित करता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | बिना सीमा के इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | इस गणितीय ब्लॉक के साथ एक गणितीय तत्व को जोड़ता है |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | इस गणितीय ब्लॉक के साथ एक गणितीय पाठ को जोड़ता है |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | अन्य गणितीय ब्लॉक को इस ब्लॉक के साथ जोड़ता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार (बार) सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | संग्रह से विशिष्ट वस्तु की पहली घटना को हटाता है। |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | संग्रह में निर्दिष्ट इंडेक्स पर तत्व को हटाता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचला सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचला सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | ह्रस्व लिपि बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | ह्रस्व लिपि बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर ह्रस्व और उच्च लिपि बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर ह्रस्व और उच्च लिपि बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर ह्रस्व और उच्च लिपि बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर ह्रस्व और उच्च लिपि बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | उच्च लिपि बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | उच्च लिपि बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्युलेटर के रूप में कार्य कर सकता है, लाइन ब्रेक पॉइंट हो सकता है, या एसे ऐसा समूह बना सकता है कि भीतर लाइन ब्रेक नहीं हो। |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | बच्चा तत्वों को एक लम्बवत सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार (बार) सेट करता है |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | इस [`MathBlock`](../mathblock) की सामग्री को MathML के रूप में सहेजता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### संबंधित देखें

* कक्षा [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathBlock](../imathblock)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->