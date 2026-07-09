---
title: ISlideCollection
second_title: Aspose.Sildes for .NET API संदर्भ
description: स्लाइड्स का एक संग्रह दर्शाता है।
type: docs
weight: 7050
url: /hi/aspose.slides/islidecollection/
---
## ISlideCollection इंटरफ़ेस

स्लाइड्स का एक संग्रह दर्शाता है।

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [`ISlide`](../islide). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | निर्दिष्ट स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | निर्दिष्ट स्लाइड की एक कॉपी निर्दिष्ट सेक्शन के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | स्रोत स्लाइड की एक कॉपी संग्रह के अंत में जोड़ता है। उपयुक्त लेआउट निर्धारित मास्टर से स्वतः चयनित होगा (उपयुक्त लेआउट वही Layout है जिसका Type या Name स्रोत स्लाइड के Layout के समान है)। यदि कोई उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का Layout क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | नई खाली स्लाइड को संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF दस्तावेज़ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है। |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF दस्तावेज़ से स्लाइड्स बनाता है और PDF आयात विकल्पों को ध्यान में रखते हुए उन्हें संग्रह के अंत में जोड़ता है। |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | संग्रह में निर्दिष्ट स्लाइड का सूचकांक लौटाता है। |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | निर्दिष्ट स्थिति में निर्दिष्ट स्लाइड की कॉपी को संग्रह में डालता है। |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | निर्दिष्ट स्थिति में निर्दिष्ट स्लाइड की कॉपी को संग्रह में डालता है। |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | निर्दिष्ट स्थिति में स्रोत स्लाइड की एक कॉपी को संग्रह में डालता है। उपयुक्त लेआउट निर्धारित मास्टर से स्वतः चयनित होगा (उपयुक्त लेआउट वही Layout है जिसका Type या Name स्रोत स्लाइड के Layout के समान है)। यदि कोई उपयुक्त लेआउट नहीं है तो स्रोत स्लाइड का Layout क्लोन किया जाएगा (यदि allowCloneMissingLayout true है) या PptxEditException फेंका जाएगा (यदि allowCloneMissingLayout false है)। |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | निर्दिष्ट स्थिति में निर्दिष्ट स्लाइड की कॉपी को संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML टेक्स्ट से स्लाइड्स बनाकर निर्दिष्ट स्थिति में संग्रह में डालता है। |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | संग्रह से विशिष्ट ऑब्जेक्ट की पहली घटना को हटाता है। |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | निर्दिष्ट सूचकांक पर संग्रह का तत्व हटाता है। |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | स्लाइड को संग्रह से निर्दिष्ट स्थिति में ले जाता है। |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | स्लाइड्स को संग्रह से निर्दिष्ट स्थिति में ले जाता है। स्लाइड्स सूची में दिखाई देने के क्रम में निर्दिष्ट सूचकांक से रखी जाएँगी। |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | सभी स्लाइड्स के साथ एक एरे बनाता है और लौटाता है। |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | निर्दिष्ट रेंज से सभी स्लाइड्स के साथ एक एरे बनाता है और लौटाता है। |

### देखें भी

* इंटरफ़ेस [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* इंटरफ़ेस [ISlide](../islide)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->