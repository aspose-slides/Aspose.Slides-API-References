---
title: MasterSlide
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक प्रस्तुति में मास्टर स्लाइड को दर्शाता है।
type: docs
weight: 8050
url: /hi/aspose.slides/masterslide/
---
## MasterSlide क्लास

एक प्रस्तुति में मास्टर स्लाइड का प्रतिनिधित्व करता है।

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## गुण

| Naam | विवरण |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | स्लाइड की पृष्ठभूमि लौटाता है। केवल पढ़ने योग्य [`IBackground`](../ibackground)। |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | बॉडी टेक्स्ट की शैली लौटाता है। केवल पढ़ने योग्य [`ITextStyle`](../itextstyle)। |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। केवल पढ़ने योग्य [`IControlCollection`](../icontrolcollection)। |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | स्लाइड का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | मास्टर स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | यदि इस मास्टर स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद हो तो true लौटाता है। केवल पढ़ने योग्य Boolean। |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | मास्टर स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल पढ़ने योग्य [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager)। |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | समाहित हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries)। |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection)। |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | मास्टर स्लाइड का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | अन्य टेक्स्ट की शैली लौटाता है। केवल पढ़ने योग्य [`ITextStyle`](../itextstyle)। |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation इंटरफ़ेस लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | निर्धारित करता है कि क्या संबंधित मास्टर को तब हटाया जाता है जब उस मास्टर के बाद सभी स्लाइड्स हटाई जाती हैं। नोट: Aspose.Slides स्वयं कोई भी अनउपयोग किया गया मास्टर नहीं हटाएगा, वास्तविक में अनउपयोग किए गए मास्टर को हटाने के लिए [`RemoveUnused`](../masterslidecollection/removeunused) कॉल करें पढ़ें/लिखें Boolean। |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | स्लाइड के शेप्स लौटाता है। केवल पढ़ने योग्य [`IShapeCollection`](../ishapecollection)। |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | निर्दिष्ट करता है कि मास्टर स्लाइड पर शेप्स को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। मास्टर स्लाइड स्वयं के लिए यह प्रॉपर्टी हमेशा `false` लौटाती है। पढ़ें/लिखें Boolean। |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | स्लाइड की ID लौटाता है। केवल पढ़ने योग्य UInt32। |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Transition ऑब्जेक्ट लौटाता है जिसमें निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है, इस बारे में जानकारी होती है। केवल पढ़ने योग्य [`ISlideShowTransition`](../islideshowtransition)। |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | थीम प्रबंधक लौटाता है। केवल पढ़ने योग्य [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager)। |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [`IAnimationTimeLine`](../ianimationtimeline)। |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | टाइटल टेक्स्ट की शैली लौटाता है। केवल पढ़ने योग्य [`ITextStyle`](../itextstyle)। |

## विधियाँ

| Naam | विवरण |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | वर्तमान मास्टर स्लाइड के आधार पर एक नया मास्टर स्लाइड बनाता है, उस पर बाहरी थीम लागू करता है और निर्मित मास्टर स्लाइड को सभी निर्भरताक्षी स्लाइड्स पर लागू करता है। |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | निर्धारित करता है कि दो IBaseSlide इंस्टेंसेस समान हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है। दो स्लाइड्स समान होती हैं यदि सभी शेप्स, स्टाइल्स, टेक्स्ट, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में यूनिक आइडेंटिफ़ायर मानों जैसे SlideId और डायनामिक कंटेंट जैसे Date Placeholder में वर्तमान तिथि मान को ध्यान में नहीं रखा जाता। |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | निर्दिष्ट वैकल्पिक टेक्स्ट वाले शेप की पहली उपस्थिति को खोजता है। |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | सभी स्लाइड्स की एक एरे लौटाता है, जो इस मास्टर स्लाइड पर निर्भर हैं। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | सभी अनुच्छेदों में सभी स्वीकार्य शेप्स में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | सभी पैराग्राफ़ों में सभी स्वीकार्य शेप्स में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |

### देखें भी

* क्लास [BaseSlide](../baseslide)
* इंटरफ़ेस [IMasterSlide](../imasterslide)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->