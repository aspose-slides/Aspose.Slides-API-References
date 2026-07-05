---
title: LayoutSlide
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक लेआउट स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 7640
url: /hi/aspose.slides/layoutslide/
---
## LayoutSlide क्लास

एक लेआउट स्लाइड का प्रतिनिधित्व करता है।

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | स्लाइड की पृष्ठभूमि लौटाता है। केवल-पढ़ने-योग्य [`IBackground`](../ibackground)। |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। केवल-पढ़ने-योग्य [`IControlCollection`](../icontrolcollection)। |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | स्लाइड का कस्टम डेटा लौटाता है। केवल-पढ़ने-योग्य [`ICustomData`](../icustomdata)। |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | लेआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने-योग्य [`IDrawingGuidesCollection`](../idrawingguidescollection)। |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | यदि इस लेआउट स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है। केवल-पढ़ने-योग्य Boolean। |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | लेआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने-योग्य [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager)। |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | शामिल हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। केवल-पढ़ने-योग्य [`IHyperlinkQueries`](../ihyperlinkqueries)। |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है। केवल-पढ़ने-योग्य [`SlideLayoutType`](../slidelayouttype)। |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। पढ़ने-और-लिखने-योग्य [`IMasterSlide`](../imasterslide)। |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | स्लाइड का नाम लौटाता या सेट करता है। पढ़ने-और-लिखने-योग्य String। |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | लेआउट स्लाइड का प्लेसहोल्डर प्रबंधक लौटाता है। केवल-पढ़ने-योग्य [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager)। |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation इंटरफ़ेस लौटाता है। केवल-पढ़ने-योग्य [`IPresentation`](../ipresentation)। |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | स्लाइड के shapes लौटाता है। केवल-पढ़ने-योग्य [`IShapeCollection`](../ishapecollection)। |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | निर्धारित करता है कि मास्टर स्लाइड पर shapes को स्लाइडों पर दिखाया जाना चाहिए या नहीं। पढ़ने-और-लिखने-योग्य Boolean। |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | स्लाइड का ID लौटाता है। केवल-पढ़ने-योग्य UInt32। |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Transition ऑब्जेक्ट लौटाता है जिसमें निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है, इसकी जानकारी होती है। केवल-पढ़ने-योग्य [`ISlideShowTransition`](../islideshowtransition)। |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | ओवरराइडिंग थीम मैनेजर लौटाता है। केवल-पढ़ने-योग्य [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)। |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | animation टाइमलाइन ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [`IAnimationTimeLine`](../ianimationtimeline)। |

## विधियां

| नाम | विवरण |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | इस स्लाइड के लिए एक प्रभावी थीम लौटाता है। |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थिर सामग्री के आधार पर गणना किया जाता है। दो स्लाइड समान होते हैं यदि सभी shapes, styles, texts, animation और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मानों, जैसे SlideId, तथा Dynamic सामग्री, जैसे Date Placeholder में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता। |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | निर्दिष्ट वैकल्पिक टेक्स्ट वाले shape की पहली उपस्थिति खोजता है। |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | उस लेआउट स्लाइड पर निर्भर सभी स्लाइडों की एक array लौटाता है। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | सभी स्वीकार्य shapes में सभी पैराग्राफ़ों में समान फ़ॉर्मेटिंग वाले runs को जोड़ता है। |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | सभी स्वीकार्य shapes में सभी पैराग्राफ़ों में समान फ़ॉर्मेटिंग वाले runs को जोड़ता है। |
| [Remove](../../aspose.slides/layoutslide/remove)() | प्रेज़ेंटेशन से लेआउट को हटाता है। |

### देखें भी

* क्लास [BaseSlide](../baseslide)
* इंटरफ़ेस [ILayoutSlide](../ilayoutslide)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->