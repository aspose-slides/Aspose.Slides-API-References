---
title: PdfOptions class
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/pdfoptions/
---
## PdfOptions क्लास

Provides options that control how a presentation is saved in Pdf format.

**विरासत:**[`PdfOptions`](/slides/python-net/hi/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)

The PdfOptions type exposes the following members:

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.export/pdfoptions/__init__/#) | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/pdfoptions/warning_callback/) | एक वस्तु लौटाता है या सेट करता है जो चेतावनियाँ प्राप्त करती है और तय करती है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी।<br/>            पढ़ें/लिखें [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/pdfoptions/progress_callback/) | प्रतिशत में सहेजने की प्रगति अद्यतनों के लिए एक कॉलबैक वस्तु को दर्शाता है।<br/>            देखें [`IProgressCallback`](/slides/python-net/hi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/pdfoptions/default_regular_font/) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **str**. |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/pdfoptions/gradient_style/) | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें [`GradientStyle`](/slides/python-net/hi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/pdfoptions/skip_java_script_links/) | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, यह निर्दिष्ट करता है। <br/>            पढ़ें/लिखें **bool**. डिफ़ॉल्ट मान **false** है। |
| [`slides_layout_options`](/slides/python-net/hi/aspose.slides.export/pdfoptions/slides_layout_options/) | प्रस्तुति को निर्यात करते समय स्लाइडों को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](/slides/python-net/hi/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/pdfoptions/ink_options/) | निर्यात दस्तावेज़ में Ink वस्तुओं की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है।<br/>            केवल पढ़ें [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/pdfoptions/show_hidden_slides/) | निर्मित दस्तावेज़ में छिपी स्लाइडें शामिल होनी चाहिए या नहीं, यह निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट है `false`. |
| [`text_compression`](/slides/python-net/hi/aspose.slides.export/pdfoptions/text_compression/) | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है।<br/>            पढ़ें/लिखें [`PdfTextCompression`](/slides/python-net/hi/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/hi/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) को स्वतः चयनित करना चाहिए या नहीं, यह दर्शाता है। <br/>            यदि **bool**.true पर सेट किया जाए, तो प्रस्तुति में प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न <br/>            एल्गोरिथ्म चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा हो जाएगा। <br/>            सर्वोत्तम छवि संपीड़न अनुपात का चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM की आवश्यकता होती है, और यह विकल्प डिफ़ॉल्ट रूप से **bool**.false है। |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/hi/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | निर्धारित करता है कि Aspose.Slides ASCII (33..127 कोड रेंज) टेक्स्ट के लिए सामान्य फ़ॉन्ट एम्बेड करेगा या नहीं।<br/>            127 से अधिक अक्षर कोड वाले फ़ॉन्ट हमेशा एम्बेड किए जाते हैं।<br/>            सामान्य फ़ॉन्ट सूची में PDF के बेस 14 फ़ॉन्ट और अतिरिक्त उपयोगकर्ता निर्दिष्ट फ़ॉन्ट शामिल हैं।<br/>            पढ़ें/लिखें **bool**. |
| [`additional_common_font_families`](/slides/python-net/hi/aspose.slides.export/pdfoptions/additional_common_font_families/) | एक ऐरे लौटाता है या सेट करता है जिसमें उपयोगकर्ता-निर्धारित फ़ॉन्ट फ़ैमिली के नाम होते हैं जिन्हें Aspose.Slides सामान्य मानना चाहिए।<br/>            पढ़ें/लिखें **str**[]. |
| [`embed_full_fonts`](/slides/python-net/hi/aspose.slides.export/pdfoptions/embed_full_fonts/) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षरों को एम्बेड किया जाना चाहिए या केवल उपयोग किया गया उपसमुह।<br/>            पढ़ें/लिखें **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/hi/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | जब फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता है तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजा जाना चाहिए या नहीं, यह दर्शाता है।<br/>            यह विधि कुछ फ़ॉन्ट्स के लिए उत्पन्न PDF में टेक्स्ट की गुणवत्ता बेहतर बना सकती है।<br/>            पढ़ें/लिखें **bool**. |
| [`jpeg_quality`](/slides/python-net/hi/aspose.slides.export/pdfoptions/jpeg_quality/) | PDF दस्तावेज़ में JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`compliance`](/slides/python-net/hi/aspose.slides.export/pdfoptions/compliance/) | निर्मित PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर।<br/>            पढ़ें/लिखें [`PdfCompliance`](/slides/python-net/hi/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/hi/aspose.slides.export/pdfoptions/password/) | PDF दस्तावेज़ को सुरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। <br/>            पढ़ें/लिखें **str**. |
| [`access_permissions`](/slides/python-net/hi/aspose.slides.export/pdfoptions/access_permissions/) | जब दस्तावेज़ उपयोगकर्ता एक्सेस के साथ खोला जाए तो किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ्लैग्स का सेट शामिल है<br/>            देखें [`PdfAccessPermissions`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/hi/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में बदलने के लिए true।<br/>            पढ़ें/लिखें **bool**. |
| [`sufficient_resolution`](/slides/python-net/hi/aspose.slides.export/pdfoptions/sufficient_resolution/) | PDF दस्तावेज़ में छवियों के रिजॉल्यूशन को निर्धारित करने वाला मान लौटाता है या सेट करता है।<br/>            <br/>यह गुण फ़ाइल आकार, निर्यात समय और छवि गुणवत्ता पर प्रभाव डालता है।<br/><br/><br/>डिफ़ॉल्ट मान **96** है।<br/><br/><br/>            पढ़ें/लिखें **float**. |
| [`draw_slides_frame`](/slides/python-net/hi/aspose.slides.export/pdfoptions/draw_slides_frame/) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true।<br/>             पढ़ें/लिखें **bool**. |
| [`image_transparent_color`](/slides/python-net/hi/aspose.slides.export/pdfoptions/image_transparent_color/) | छवि के पारदर्शी रंग को प्राप्त करता है या सेट करता है. |
| [`apply_image_transparent`](/slides/python-net/hi/aspose.slides.export/pdfoptions/apply_image_transparent/) | यदि `true` है तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है. |
| [`include_ole_data`](/slides/python-net/hi/aspose.slides.export/pdfoptions/include_ole_data/) | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true।<br/>            पढ़ें/लिखें **bool**. |

### देखें
* क्लास [`PdfOptions`](/slides/python-net/hi/aspose.slides.export/pdfoptions)
* क्लास [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)