---
title: MasterSlide
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक प्रेजेंटेशन में मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 8030
url: /hi/aspose.slides/masterslide/
---
## MasterSlide क्लास

प्रेजेंटेशन में एक मास्टर स्लाइड का प्रतिनिधित्व करता है।

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | स्लाइड की पृष्ठभूमि लौटाता है। केवल-पढ़ने योग्य [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | बॉडी टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | स्लाइड पर ActiveX कंट्रोल्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | स्लाइड के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | मास्टर स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-pढ़ने योग्य [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | यदि कम से कम एक स्लाइड है जो इस मास्टर स्लाइड पर निर्भर करती है तो true लौटाता है। केवल-पढ़ने योग्य Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | मास्टर स्लाइड का HeaderFooter मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | समाहित हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। केवल-पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | मास्टर स्लाइड का नाम लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | अन्य टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | निर्धारित करता है कि सभी स्लाइड्स हटाने पर संबंधित मास्टर हटाया जाए या नहीं। नोट: Aspose.Slides कभी भी स्वचालित रूप से अनउपयोगित मास्टर नहीं हटाएगा, अनउपयोगित मास्टर को हटाने के लिए [`RemoveUnused`](../masterslidecollection/removeunused) को कॉल करें। पढ़ने/लिखने योग्य Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | स्लाइड के शेप्स लौटाता है। केवल-पढ़ने योग्य [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | निर्धारित करता है कि मास्टर स्लाइड पर शेप्स स्लाइड्स पर दिखाए जाएँ या न दिखें। स्वयं मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा `false` लौटाती है। पढ़ने/लिखने योग्य Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | स्लाइड की ID लौटाता है। केवल-पड़ने योग्य UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | वह Transition ऑब्जेक्ट लौटाता है जिसमें यह जानकारी होती है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है। केवल-पढ़ने योग्य [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | थीम मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | टाइटल टेक्स्ट की शैली लौटाता है। केवल-पढ़ने योग्य [`ITextStyle`](../itextstyle). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | वर्तमान मास्टर स्लाइड के आधार पर एक नई मास्टर स्लाइड बनाता है, उस पर बाहरी थीम लागू करता है और बनाई गई मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है। |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | निर्धारित करता है कि दो IBaseSlide इंस्टेंस समान हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है। दो स्लाइड समान हैं यदि सभी शेप्स, शैली, टेक्स्ट, एनिमेशन और अन्य सेटिंग्स आदि समान हों। तुलना अद्वितीय पहचानकर्ता मानों, जैसे SlideId, और गतिशील सामग्री, जैसे Date Placeholder में वर्तमान तिथि मान, को ध्यान में नहीं रखती। |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | निर्दिष्ट वैकल्पिक टेक्स्ट वाले शेप की पहली उपस्थिति खोजता है। |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | सभी स्लाइड्स की एक एरे लौटाता है जो इस मास्टर स्लाइड पर निर्भर हैं। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | सभी स्वीकार्य शेप्स में सभी पैराग्राफ़ के समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | सभी स्वीकार्य शेप्स में सभी पैराग्राफ़ के समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |

### देखें

* क्लास [BaseSlide](../baseslide)
* इंटरफ़ेस [IMasterSlide](../imasterslide)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->