---
title: Slide
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक प्रस्तुति में स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 9980
url: /hi/aspose.slides/slide/
---
## Slide वर्ग

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## गुण

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | स्लाइड की पृष्ठभूमि लौटाता है। केवल-पढ़ने योग्य [`IBackground`](../ibackground)। |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IControlCollection`](../icontrolcollection)। |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | स्लाइड का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | स्लाइड के HeaderFooter प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [`ISlideHeaderFooterManager`](../islideheaderfootermanager)। |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | निर्धारित करता है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान छिपी है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | समाहित हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल-पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries)। |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`ILayoutSlide`](../ilayoutslide)। |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | स्लाइड का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | नोट्स स्लाइड तक पहुँच की अनुमति देता है, इसे जोड़ता और हटाता है। केवल-पढ़ने योग्य [`INotesSlideManager`](../inotesslidemanager)। |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | स्लाइड के आकृतियों को लौटाता है। केवल-पढ़ने योग्य [`IShapeCollection`](../ishapecollection)। |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | निर्दिष्ट करता है कि मास्टर स्लाइड की आकृतियाँ स्लाइडों पर दिखनी चाहिए या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | स्लाइड का ID लौटाता है। केवल-पढ़ने योग्य UInt32। |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | स्लाइड की संख्या लौटाता है। [`Slides`](../presentation/slides) संग्रह में स्लाइड का अनुक्रमांक हमेशा SlideNumber - Presentation.FirstSlideNumber के बराबर रहता है। पढ़ने/लिखने योग्य Int32। |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | वह Transition ऑब्जेक्ट लौटाता है जिसमें निर्दिष्ट स्लाइड के स्लाइड शो के दौरान आगे बढ़ने की जानकारी होती है। केवल-पढ़ने योग्य [`ISlideShowTransition`](../islideshowtransition)। |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | ओवरराइडिंग थीम प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)। |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | एनिमेशन टाइमलाइन ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`IAnimationTimeLine`](../ianimationtimeline)। |

## विधियाँ

| Name | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | इस स्लाइड के लिए एक प्रभावी थीम लौटाता है। |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थिर सामग्री के आधार पर गणना किया जाता है। दो स्लाइड समान होती हैं यदि सभी आकृतियाँ, शैलियाँ, पाठ, एनिमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान जैसे SlideId और गतिशील सामग्री जैसे तिथि प्लेसहोल्डर में वर्तमान तिथि मान को ध्यान में नहीं रखा जाता। |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | निर्दिष्ट वैकल्पिक पाठ वाले आकृति की पहली उपस्थिति ढूँढता है। |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | एक Thumbnail Image ऑब्जेक्ट लौटाता है (वास्तविक आकार का 20%)। |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | निर्दिष्ट पैरामीटरों के साथ एक Thumbnail tiff इमेज ऑब्जेक्ट लौटाता है। |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | निर्दिष्ट आकार के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | कस्टम स्केलिंग के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | निर्दिष्ट आकार के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | कस्टम स्केलिंग के साथ एक Thumbnail Image ऑब्जेक्ट लौटाता है। |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | विशिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणी लौटाता है। |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | सभी स्वीकार्य आकृतियों में सभी पैराग्राफ़ों में समान स्वरूप के रन को जोड़ता है। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | सभी स्वीकार्य आकृतियों में सभी पैराग्राफ़ों में समान स्वरूप के रन को जोड़ता है। |
| [Remove](../../aspose.slides/slide/remove)() | प्रेजेंटेशन से स्लाइड को हटाता है। |
| [Reset](../../aspose.slides/slide/reset)() | LayoutSlide पर प्रोटोटाइप वाले प्रत्येक आकृति की स्थिति, आकार और स्वरूप को रीसेट करता है। |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | स्लाइड की सामग्री को EMF फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | स्लाइड की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | स्लाइड की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* वर्ग [BaseSlide](../baseslide)
* इंटरफ़ेस [ISlide](../islide)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->