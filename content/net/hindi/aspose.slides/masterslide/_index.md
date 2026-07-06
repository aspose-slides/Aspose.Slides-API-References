---
title: MasterSlide
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक प्रस्तुति में मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 8030
url: /hi/aspose.slides/masterslide/
---
## MasterSlide वर्ग

एक प्रस्तुति में मास्टर स्लाइड का प्रतिनिधित्व करता है।

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | स्लाइड की पृष्ठभूमि लौटाता है। केवल-पढ़ने योग्य [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | बॉडी टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | स्लाइड के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | मास्टर स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | यदि कम से कम एक स्लाइड इस मास्टर स्लाइड पर निर्भर हो, तो true लौटाता है। केवल-पढ़ने योग्य Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | मास्टर स्लाइड के HeaderFooter प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | समाहित हाइपरलिंक तक आसान पहुंच प्रदान करता है। केवल-पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | मास्टर स्लाइड का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | अन्य टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | निर्धारित करता है कि सभी स्लाइड्स जो उस मास्टर के बाद आते हैं, हट जाने पर संबंधित मास्टर हटाया जाता है या नहीं। नोट: Aspose.Slides स्वयं कोई अनउपयोगित मास्टर नहीं हटाएगा, अनउपयोगित मास्टर को वास्तव में हटाने के लिए [`RemoveUnused`](../masterslidecollection/removeunused) कॉल करें। पढ़ें/लिखें Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | स्लाइड के शेप्स को लौटाता है। केवल-पढ़ने योग्य [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | निर्देशित करता है कि मास्टर स्लाइड पर शेप्स स्लाइड्स पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा `false` लौटाती है। पढ़ें/लिखें Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | स्लाइड की ID लौटाता है। केवल-पढ़ने योग्य UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है, इस बारे में जानकारी वाला Transition ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | थीम प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | टाइटल टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | वर्तमान मास्टर स्लाइड के आधार पर एक नई मास्टर स्लाइड बनाता है, उस पर एक बाहरी थीम लागू करता है और बनाई गई मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है। |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | इस स्लाइड के लिए एक प्रभावी थीम लौटाता है। |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | निर्धारित करता है कि दो IBaseSlide इंस्टैंसेज़ समान हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थिर सामग्री के आधार पर गणना किया जाता है। दो स्लाइड्स समान तब मानी जाती हैं जब सभी शेप्स, शैलियां, टेक्स्ट, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान जैसे SlideId और गतिशील सामग्री जैसे Date Placeholder में वर्तमान तिथि मान को ध्यान में नहीं रखा जाता है। |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | निर्दिष्ट वैकल्पिक टेक्स्ट के साथ शेप की पहली मौजूदगी खोजता है। |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | एक एरे लौटाता है जिसमें सभी स्लाइड्स होते हैं जो इस मास्टर स्लाइड पर निर्भर हैं। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | सभी अनुच्छेदों और सभी उपयुक्त शेप्स में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | सभी अनुच्छेदों और सभी उपयुक्त शेप्स में समान फॉर्मेटिंग वाले रन को जोड़ता है। |

### देखें भी

* वर्ग [BaseSlide](../baseslide)
* इंटरफ़ेस [IMasterSlide](../imasterslide)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->