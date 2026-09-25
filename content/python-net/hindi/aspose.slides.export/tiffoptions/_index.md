---
title: TiffOptions class
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.export/tiffoptions/
---
## TiffOptions क्लास

एक प्रस्तुति को TIFF प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

**विरासत:**[`TiffOptions`](/slides/python-net/hi/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)

TiffOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## कन्स्ट्रक्टर्स

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.export/tiffoptions/__init__/#) | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## गुण

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/tiffoptions/warning_callback/) | एक ऑब्जेक्ट लौटाता है या सेट करता है जो चेतावनियाँ प्राप्त करता है और यह निर्धारित करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी।<br/>            पढ़ें/लिखें [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/tiffoptions/progress_callback/) | प्रतिशत में प्रगति अपडेट को सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है।<br/>            देखें [`IProgressCallback`](/slides/python-net/hi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/tiffoptions/default_regular_font/) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है।<br/>            पढ़ें-लिखें **str**. |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/tiffoptions/gradient_style/) | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें [`GradientStyle`](/slides/python-net/hi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/tiffoptions/skip_java_script_links/) | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **bool**. डिफ़ॉल्ट मान **false** है। |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/tiffoptions/ink_options/) | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है।<br/>            केवल-पढ़ने योग्य [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/tiffoptions/show_hidden_slides/) | निर्मित दस्तावेज़ में छिपी स्लाइड्स शामिल करनी हैं या नहीं, निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट `false` है। |
| [`image_size`](/slides/python-net/hi/aspose.slides.export/tiffoptions/image_size/) | निर्मित TIFF छवि का आकार निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि छवि का आकार प्रस्तुति स्लाइड आकार के आधार पर गणना किया जाएगा।<br/>            पढ़ें/लिखें [`Size`](/slides/python-net/hi/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/hi/aspose.slides.export/tiffoptions/dpi_x/) | डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`dpi_y`](/slides/python-net/hi/aspose.slides.export/tiffoptions/dpi_y/) | डॉट्स प्रति इंच में लंबवत रिज़ॉल्यूशन निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`compression_type`](/slides/python-net/hi/aspose.slides.export/tiffoptions/compression_type/) | संपीड़न प्रकार निर्दिष्ट करता है।<br/>            पढ़ें/लिखें [`TiffCompressionTypes`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/hi/aspose.slides.export/tiffoptions/pixel_format/) | निर्मित छवियों के लिए पिक्सेल प्रारूप निर्दिष्ट करता है।<br/>            पढ़ें/लिखें [`ImagePixelFormat`](/slides/python-net/hi/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/hi/aspose.slides.export/tiffoptions/slides_layout_options/) | प्रस्तुति निर्यात करते समय स्लाइडों को पृष्ठ पर जिस मोड में रखा जाता है, उसे प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](/slides/python-net/hi/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/hi/aspose.slides.export/tiffoptions/bw_conversion_mode/) | एक रंगीन छवि को काली और सफ़ेद छवि में बदलने के लिए एल्गोरिद्म निर्दिष्ट करता है।<br/>            यह विकल्प केवल तब लागू होगा जब [`TiffOptions.compression_type`](/slides/python-net/hi/aspose.slides.export/tiffoptions/compression_type) <br/>            को [`TiffCompressionTypes.CCITT4`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes/CCITT4) या [`TiffCompressionTypes.CCITT3`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes/CCITT3) पर सेट किया गया हो<br/>            पढ़ें/लिखें [`BlackWhiteConversionMode`](/slides/python-net/hi/aspose.slides.export/blackwhiteconversionmode).<br/>            डिफ़ॉल्ट [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/hi/aspose.slides.export/blackwhiteconversionmode/DEFAULT) है। |


### देखें
* क्लास [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)
* क्लास [`TiffOptions`](/slides/python-net/hi/aspose.slides.export/tiffoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)