---
title: ISlideCollection
second_title: Aspose.Sildes for .NET API संदर्भ
description: स्लाइडों का एक संग्रह दर्शाता है।
type: docs
weight: 7050
url: /hi/aspose.slides/islidecollection/
---
## ISlideCollection इंटरफ़ेस

स्लाइडों का एक संग्रह दर्शाता है।

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [`ISlide`](../islide). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | निर्दिष्ट स्लाइड की एक प्रति को संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | निर्दिष्ट स्लाइड की एक प्रति को संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | निर्दिष्ट अनुभाग के अंत में निर्दिष्ट स्लाइड की एक प्रति जोड़ता है। |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | निर्दिष्ट स्रोत स्लाइड की एक प्रति को संग्रह के अंत में जोड़ता है। उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चुना जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका प्रकार या नाम स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | संग्रह के अंत में एक नई खाली स्लाइड जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF दस्तावेज़ से स्लाइड बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF दस्तावेज़ से स्लाइड बनाता है और PDF आयात विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है। |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | संग्रह में निर्दिष्ट स्लाइड का अनुक्रमणिका लौटाता है। |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | निर्दिष्ट स्थिति में निर्दिष्ट स्लाइड की एक प्रति सम्मिलित करता है। |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | निर्दिष्ट स्थिति में निर्दिष्ट स्लाइड की एक प्रति सम्मिलित करता है। |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | निर्दिष्ट स्रोत स्लाइड की एक प्रति को संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। उपयुक्त लेआउट निर्दिष्ट मास्टर से स्वचालित रूप से चुना जाएगा (उपयुक्त लेआउट वह लेआउट है जिसका प्रकार या नाम स्रोत स्लाइड के लेआउट के समान है)। यदि उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का लेआउट क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | निर्दिष्ट स्थिति में निर्दिष्ट स्लाइड की एक प्रति सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML पाठ से स्लाइड बनाता है और उन्हें संग्रह की निर्दिष्ट स्थिति में सम्मिलित करता है। |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | संग्रह से विशेष वस्तु की पहली उपस्थिति को हटाता है। |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | संग्रह में निर्दिष्ट अनुक्रमणिका पर तत्व को हटाता है। |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | संग्रह से स्लाइड को निर्दिष्ट स्थिति में ले जाता है। |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | संग्रह से स्लाइडों को निर्दिष्ट स्थिति में ले जाता है। स्लाइडें सूची में दिखाई देने के क्रम में अनुक्रमणिका से शुरू होकर रखी जाएँगी। |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | सभी स्लाइडों के साथ एक एरे बनाता है और लौटाता है। |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | निर्दिष्ट सीमा के सभी स्लाइडों के साथ एक एरे बनाता है और लौटाता है। |

### देखें

* इंटरफ़ेस [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* इंटरफ़ेस [ISlide](../islide)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->