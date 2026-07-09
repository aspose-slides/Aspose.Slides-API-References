---
title: SlideCollection
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: स्लाइड्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
weight: 9970
url: /hi/aspose.slides/slidecollection/
---
## SlideCollection क्लास

एक स्लाइड के संग्रह का प्रतिनिधित्व करता है।

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | संग्रह में वास्तविक रूप से सम्मिलित तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | एक मान लौटाता है जो संकेत देता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ) है या नहीं। केवल पढ़ने योग्य Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | एक समकालिककरण मूल लौटाता है। केवल पढ़ने योग्य Object. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | निर्दिष्ट स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | निर्दिष्ट स्लाइड की एक प्रति निर्दिष्ट अनुभाग के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह के अंत में जोड़ता है। उपयुक्त लेआउट स्वचालित रूप से निर्दिष्ट मास्टर से चयनित किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका प्रकार या नाम स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)। |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | एक नया खाली स्लाइड संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF दस्तावेज़ से स्लाइड बनाता है और PDF आयात विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है। |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | एक इटेरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृत्ति करता है। |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | संग्रह में निर्दिष्ट स्लाइड का अनुक्रमांक लौटाता है। |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | निर्दिष्ट स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | निर्दिष्ट स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | निर्दिष्ट स्रोत स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। उपयुक्त लेआउट स्वचालित रूप से निर्दिष्ट मास्टर से चयनित किया जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका प्रकार या नाम स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout सत्य है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout असत्य है)। |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | निर्दिष्ट स्लाइड की एक प्रति संग्रह में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML टेक्स्ट से स्लाइड बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है। |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | संग्रह से किसी विशिष्ट वस्तु की पहली उपस्थिति को हटाता है। |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | संग्रह में निर्दिष्ट अनुक्रमांक पर तत्व को हटाता है। |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | स्लाइड को संग्रह से निकालकर निर्दिष्ट स्थिति पर ले जाता है। |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | स्लाइडों को संग्रह से निकालकर निर्दिष्ट स्थिति पर ले जाता है। स्लाइडें सूची में जो क्रम में दिखाई देती हैं, उस क्रम में अनुक्रमांक से शुरू होकर रखी जाएँगी। |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | सभी स्लाइडों के साथ एक एरे बनाता है और लौटाता है। |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | निर्दिष्ट सीमा के सभी स्लाइडों के साथ एक एरे बनाता है और लौटाता है। जोड़ने के लिए प्रथम स्लाइड का अनुक्रमांक। जोड़ने के लिए स्लाइडों की संख्या। |

### संबंधित देखें

* क्लास [DomObject&lt;TParent&gt;](../domobject-1)
* क्लास [Presentation](../presentation)
* इंटरफ़ेस [ISlideCollection](../islidecollection)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->