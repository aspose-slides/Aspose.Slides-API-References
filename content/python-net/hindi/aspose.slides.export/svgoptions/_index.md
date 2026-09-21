---
title: SVGOptions class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/svgoptions/
---
## SVGOptions क्लास

एक SVG विकल्प का प्रतिनिधित्व करता है।

**विरासत:**[`SVGOptions`](/slides/python-net/hi/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)

SVGOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## कन्स्ट्रक्टर

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.export/svgoptions/__init__/#) | SVGOptions क्लास का एक नया उदाहरण आरंभ करता है। |
| [`__init__(self, link_embed_controller)`](/slides/python-net/hi/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | SVGOptions क्लास का एक नया उदाहरण आरंभ करता है जिसमें लिंक एम्बेडिंग कंट्रोलर ऑब्जेक्ट निर्दिष्ट किया गया है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/svgoptions/warning_callback/) | एक ऑब्जेक्ट लौटाता है या सेट करता है जो चेतावनियों को प्राप्त करता है और यह निर्णय लेता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी।<br/>            Read/write [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/svgoptions/progress_callback/) | प्रतिशत में प्रगति अपडेट सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है।<br/>            देखें [`IProgressCallback`](/slides/python-net/hi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/svgoptions/default_regular_font/) | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है।<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/svgoptions/gradient_style/) | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है।<br/>            Read/write [`GradientStyle`](/slides/python-net/hi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/svgoptions/skip_java_script_links/) | प्रेजेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, यह निर्दिष्ट करता है। <br/>            Read/write **bool**. डिफ़ॉल्ट मान **false** है। |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/svgoptions/ink_options/) | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है।<br/>            Read-only [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/hi/aspose.slides.export/svgoptions/use_frame_size/) | निर्धारित करता है कि टेक्स्ट फ्रेम रेंडरिंग क्षेत्र में शामिल होगा या नहीं।<br/>            Read/write **bool**.<br/>            डिफ़ॉल्ट मान false है। |
| [`use_frame_rotation`](/slides/python-net/hi/aspose.slides.export/svgoptions/use_frame_rotation/) | रेंडरिंग के दौरान शैप की निर्दिष्ट घुमाव को लागू करना है या नहीं, निर्धारित करता है।<br/>            Read/write **bool**.<br/>            डिफ़ॉल्ट मान true है। |
| [`vectorize_text`](/slides/python-net/hi/aspose.slides.export/svgoptions/vectorize_text/) | स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं, निर्धारित करता है।<br/>            Read/write **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/hi/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | मेटा फ़ाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को लौटाता है या सेट करता है।<br/>            Read/write **int**. |
| [`disable_3d_text`](/slides/python-net/hi/aspose.slides.export/svgoptions/disable_3d_text/) | SVG में 3D टेक्स्ट निष्क्रिय है या नहीं, निर्धारित करता है।<br/>            Read/write **bool**. |
| [`disable_gradient_split`](/slides/python-net/hi/aspose.slides.export/svgoptions/disable_gradient_split/) | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है।<br/>            Read/write **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/hi/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 में मार्करों के लिए इनसेट परिभाषित करने की क्षमता नहीं है।<br/>            Aspose.Slides SVG लेखन इंजन ने इस समस्या के लिए समाधान प्रदान किया है:<br/>            यह तीर के साथ लाइन का अंत काट देता है, ताकि लाइन मार्करों के साथ ओवरलैप न करे।<br/>            यह विकल्प ऐसा व्यवहार बंद कर देता है।<br/>            Read/write **bool**. |
| [`default`](/slides/python-net/hi/aspose.slides.export/svgoptions/default/) | डिफ़ॉल्ट सेटिंग्स लौटाता है।<br/>            Read-only [`SVGOptions`](/slides/python-net/hi/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/hi/aspose.slides.export/svgoptions/simple/) | सबसे सरल और सबसे छोटा SVG फ़ाइल जनरेशन के लिए सेटिंग्स लौटाता है।<br/>            Read-only [`SVGOptions`](/slides/python-net/hi/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/hi/aspose.slides.export/svgoptions/wysiwyg/) | सबसे सटीक SVG फ़ाइल जनरेशन के लिए सेटिंग्स लौटाता है।<br/>            Read-only [`SVGOptions`](/slides/python-net/hi/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/hi/aspose.slides.export/svgoptions/jpeg_quality/) | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है।<br/>            Read/write **int**. |
| [`shape_formatting_controller`](/slides/python-net/hi/aspose.slides.export/svgoptions/shape_formatting_controller/) | उपयोगकर्ता को शैप रूपांतरण को नियंत्रित करने की अनुमति देने वाला कॉलबैक इंटरफ़ेस लौटाता है और सेट करता है।<br/>            Read/write [`ISvgShapeFormattingController`](/slides/python-net/hi/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/hi/aspose.slides.export/svgoptions/pictures_compression/) | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है |
| [`delete_pictures_cropped_areas`](/slides/python-net/hi/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | एक बूलियन फ़्लैग दर्शाता है कि क्या कटे हुए भाग दस्तावेज़ का हिस्सा बने रहेंगे। यदि true हो तो कटे हुए <br/>            भाग हटा दिए जाएंगे, यदि false हो तो वे दस्तावेज़ में क्रमबद्ध किए जाएंगे (जो संभवतः बड़े फ़ाइल का कारण बन सकता है)। |
| [`external_fonts_handling`](/slides/python-net/hi/aspose.slides.export/svgoptions/external_fonts_handling/) | बाहरी रूप से लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है।<br/>            Read/write [`SvgExternalFontsHandling`](/slides/python-net/hi/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/hi/aspose.slides.export/svgoptions/disable_font_ligatures/) | यह मूल्य निर्धारित करता है या सेट करता है कि टेक्स्ट को लिगेचर के बिना रेंडर किया जाए या नहीं।<br/>            जब `true` पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह गुण `false` पर सेट होता है। |

### संबंधित देखें
* क्लास [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)
* क्लास [`SVGOptions`](/slides/python-net/hi/aspose.slides.export/svgoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)