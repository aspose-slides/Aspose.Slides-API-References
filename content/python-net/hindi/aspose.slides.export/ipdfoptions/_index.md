---
title: IPdfOptions class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/ipdfoptions/
---
## IPdfOptions क्लास

Provides options that control how a presentation is saved in Pdf format.

The IPdfOptions type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/text_compression/) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है।<br/>            पढ़ें/लिखें [`PdfTextCompression`](/slides/python-net/hi/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | यह संकेत देता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चुना जाना चाहिए <br/>            स्वचालित रूप से। यदि इसे **bool**.true पर सेट किया जाता है, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न <br/>            एल्गोरिद्म चुना जाएगा, जिससे परिणामी PDF दस्तावेज़ का आकार छोटा हो जाएगा। <br/>            सर्वोत्तम छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM उपयोग करता है, और यह विकल्प डिफ़ॉल्ट रूप से **bool**.false है। |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | ASCII अक्षर 32-127 के लिए true type फ़ॉन्ट एम्बेड करने के लिए सही।<br/>            127 से बड़े अक्षर कोड वाले फ़ॉन्ट हमेशा एम्बेड होते हैं।<br/>            पढ़ें/लिखें **bool**. |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/show_hidden_slides/) | निर्मित दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं, यह निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट `false` है। |
| [`additional_common_font_families`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/additional_common_font_families/) | फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक एरे लौटाता है या सेट करता है जिसे Aspose.Slides सामान्य मानता है।<br/>            पढ़ें/लिखें **str**[]. |
| [`embed_full_fonts`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/embed_full_fonts/) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किया गया उपसमुच्चय।<br/>            पढ़ें/लिखें **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | यह दर्शाता है कि फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता तो पाठ को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजा जाए।<br/>            यह विधि कुछ फ़ॉन्ट्स के लिए परिणामी PDF में पाठ की गुणवत्ता बढ़ा सकती है।<br/>            पढ़ें/लिखें **bool**. |
| [`jpeg_quality`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/jpeg_quality/) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`compliance`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/compliance/) | निर्मित PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर।<br/>            पढ़ें/लिखें [`PdfCompliance`](/slides/python-net/hi/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/password/) | PDF दस्तावेज़ को सुरक्षित रखने के लिए उपयोगकर्ता पासवर्ड सेट करना। <br/>            पढ़ें/लिखें **str**. |
| [`access_permissions`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/access_permissions/) | दस्तावेज़ उपयोगकर्ता पहुँच के साथ खुले तो किन अभिगम अधिकारों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का सेट सम्मिलित करता है<br/>           । देखें [`PdfAccessPermissions`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | प्रस्तुति में उपयोग किए गए सभी मेटाफाइल्स को PNG छवियों में परिवर्तित करने के लिए सही।<br/>            पढ़ें/लिखें **bool**. |
| [`sufficient_resolution`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/sufficient_resolution/) | PDF दस्तावेज़ के भीतर छवियों का रिज़ॉल्यूशन निर्धारित करने वाला मान लौटाता है या सेट करता है।<br/>            <br/>गुण फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता को प्रभावित करता है।<br/><br/><br/>डिफ़ॉल्ट मान **96** है।<br/><br/><br/>            पढ़ें/लिखें **float**. |
| [`draw_slides_frame`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/draw_slides_frame/) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम बनाने के लिए सही।<br/>            पढ़ें/लिखें **bool**. |
| [`slides_layout_options`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/slides_layout_options/) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](/slides/python-net/hi/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/image_transparent_color/) | छवि के पारदर्शी रंग को प्राप्त करता है या सेट करता है। |
| [`apply_image_transparent`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/apply_image_transparent/) | यदि `true` हो, तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/ink_options/) | निर्यातित दस्तावेज़ में Ink वस्तुओं की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है।<br/>            केवल पढ़ने योग्य [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/include_ole_data/) | प्रस्तुति में उपयोग किए गए सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए सही।<br/>            पढ़ें/लिखें **bool**. |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)