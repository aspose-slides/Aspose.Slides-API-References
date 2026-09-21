---
title: HtmlOptions class
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/htmloptions/
---
## HtmlOptions क्लास

HTML निर्यात विकल्पों का प्रतिनिधित्व करता है।

**Inheritance:**[`HtmlOptions`](/slides/python-net/hi/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)

HtmlOptions प्रकार निम्न सदस्य उजागर करता है:

## कॉन्स्ट्रक्टर्स

| Constructor | Description |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/hi/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | एक नया HtmlOptions ऑब्जेक्ट बनाता है जो कॉलबैक निर्दिष्ट करता है। |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.export/htmloptions/__init__/#) | एक नया HtmlOptions ऑब्जेक्ट बनाता है जो एकल HTML फ़ाइल में सहेजने के लिए है। |

## प्रॉपर्टीज़

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/htmloptions/warning_callback/) | उन चेतावनियों को प्राप्त करने वाले और यह तय करने वाले ऑब्जेक्ट को लौटाता/सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी।<br/>            Read/write [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/htmloptions/progress_callback/) | सहेजने की प्रगति अपडेट्स को प्रतिशत में दर्शाने वाले कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है।<br/>            See [`IProgressCallback`](/slides/python-net/hi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/htmloptions/default_regular_font/) | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को लौटाता/सेट करता है।<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/htmloptions/gradient_style/) | ग्रेडिएंट की दृश्य शैली को लौटाता/सेट करता है।<br/>            Read/write [`GradientStyle`](/slides/python-net/hi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/htmloptions/skip_java_script_links/) | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ने को निर्दिष्ट करता है। <br/>            Read/write **bool**. डिफ़ॉल्ट मान **false** है। |
| [`slides_layout_options`](/slides/python-net/hi/aspose.slides.export/htmloptions/slides_layout_options/) | प्रस्तुति निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को प्राप्त या सेट करता है [`ISlidesLayoutOptions`](/slides/python-net/hi/aspose.slides.export/islideslayoutoptions)। |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/htmloptions/ink_options/) | निर्यात दस्तावेज़ में Ink ऑब्जेक्ट्स के दिखावे को नियंत्रित करने वाले विकल्प प्रदान करता है।<br/>            Read-only [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/htmloptions/show_hidden_slides/) | उत्पन्न दस्तावेज़ में छिपी स्लाइड्स को शामिल किया जाए या न हो, इसे निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट `false` है। |
| [`html_formatter`](/slides/python-net/hi/aspose.slides.export/htmloptions/html_formatter/) | HTML टेम्पलेट को लौटाता/सेट करता है।<br/>            Read/write [`IHtmlFormatter`](/slides/python-net/hi/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/hi/aspose.slides.export/htmloptions/disable_font_ligatures/) | यह बताता है कि पाठ लिगेचर का उपयोग किए बिना रेंडर किया जाए या नहीं।<br/>            जब `true` पर सेट किया जाता है, लिगेचर रेंडर आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से यह प्रॉपर्टी `false` पर सेट होती है। |
| [`slide_image_format`](/slides/python-net/hi/aspose.slides.export/htmloptions/slide_image_format/) | स्लाइड इमेज फ़ॉर्मेट विकल्पों को लौटाता/सेट करता है।<br/>            Read/write [`ISlideImageFormat`](/slides/python-net/hi/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/hi/aspose.slides.export/htmloptions/jpeg_quality/) | PDF दस्तावेज़ में JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता/सेट करता है।<br/>            Read/write **int**. |
| [`pictures_compression`](/slides/python-net/hi/aspose.slides.export/htmloptions/pictures_compression/) | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है |
| [`delete_pictures_cropped_areas`](/slides/python-net/hi/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | एक बूलियन फ़्लैग जो दर्शाता है कि क्रॉप की गई भागें दस्तावेज़ का हिस्सा बनी रहेंगी या नहीं। यदि true है तो क्रॉप की गई भागें हटा दी जाएँगी, यदि false है तो वे दस्तावेज़ में सीरिएलाइज़ हो जाएँगी (जिससे फ़ाइल आकार बड़ा हो सकता है) |
| [`svg_responsive_layout`](/slides/python-net/hi/aspose.slides.export/htmloptions/svg_responsive_layout/) | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को बाहर रखने के लिए true सेट करें – इससे लेआउट उत्तरदायी बन जाएगा। अन्यथा false सेट करें।<br/>            Read/write **bool**. |


### See Also
* क्लास [`HtmlOptions`](/slides/python-net/hi/aspose.slides.export/htmloptions)
* क्लास [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)