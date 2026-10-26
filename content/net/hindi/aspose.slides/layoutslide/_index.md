---
title: LayoutSlide
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक लेआउट स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 7640
url: /hi/aspose.slides/layoutslide/
---
## LayoutSlide क्लास

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | स्लाइड की पृष्ठभूमि लौटाता है। केवल पढ़ने योग्य [`IBackground`](../ibackground)। |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। केवल पढ़ने योग्य [`IControlCollection`](../icontrolcollection)। |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | स्लाइड का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | लेआउट स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [`IDrawingGuidesCollection`](../idrawingguidescollection)। |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | यदि कम से कम एक स्लाइड इस लेआउट स्लाइड पर निर्भर करता है तो true लौटाता है। केवल पढ़ने योग्य Boolean। |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | लेआउट स्लाइड के HeaderFooter प्रबंधक को लौटाता है। केवल पढ़ने योग्य [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager)। |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | निहित हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल पढ़ने योग्य [`IHyperlinkQueries`](../ihyperlinkqueries)। |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है। केवल पढ़ने योग्य [`SlideLayoutType`](../slidelayouttype)। |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। पढ़ें/लिखें [`IMasterSlide`](../imasterslide)। |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | स्लाइड का नाम लौटाता या सेट करता है। पढ़ें/लिखें String। |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | लेआउट स्लाइड के प्लेसहोल्डर प्रबंधक को लौटाता है। केवल पढ़ने योग्य [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager)। |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation इंटरफ़ेस को लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | स्लाइड के आकारों को लौटाता है। केवल पढ़ने योग्य [`IShapeCollection`](../ishapecollection)। |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | निर्धारित करता है कि क्या मास्टर स्लाइड पर आकारों को स्लाइडों पर दिखाया जाना चाहिए या नहीं। पढ़ें/लिखें Boolean। |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | स्लाइड का ID लौटाता है। केवल पढ़ने योग्य UInt32। |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | ट्रांज़िशन ऑब्जेक्ट लौटाता है जो निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है, की जानकारी रखता है। केवल पढ़ने योग्य [`ISlideShowTransition`](../islideshowtransition)। |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | ओवरराइडिंग थीम प्रबंधक को लौटाता है। केवल पढ़ने योग्य [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)। |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [`IAnimationTimeLine`](../ianimationtimeline)। |

## विधियां

| नाम | विवरण |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | निर्धारित करता है कि क्या दो IBaseSlide इंस्टेंस समान हैं। लौटाया गया मान स्लाइड की संरचना और स्थिर सामग्री के आधार पर गणना किया जाता है। दो स्लाइड समान होते हैं यदि सभी आकार, शैलियाँ, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान जैसे SlideId और गतिशील सामग्री जैसे वर्तमान तिथि मान Date Placeholder में नहीं लिया जाता है। |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली घटना खोजता है। |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | एक एरे लौटाता है जिसमें सभी स्लाइड्स होते हैं, जो इस लेआउट स्लाइड पर निर्भर करते हैं। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | सभी पैराग्राफ़ों और सभी स्वीकार्य आकारों में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | सभी पैराग्राफ़ों और सभी स्वीकार्य आकारों में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| [Remove](../../aspose.slides/layoutslide/remove)() | प्रेजेंटेशन से लेआउट हटाता है। |

### देखें भी

* क्लास [BaseSlide](../baseslide)
* इंटरफ़ेस [ILayoutSlide](../ilayoutslide)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->