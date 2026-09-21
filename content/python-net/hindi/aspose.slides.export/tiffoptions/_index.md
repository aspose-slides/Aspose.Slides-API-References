---
title: TiffOptions class
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/tiffoptions/
---
## TiffOptions वर्ग

विकल्प प्रदान करता है जो नियंत्रित करता है कि प्रस्तुति TIFF फ़ॉर्मेट में कैसे सहेजी जाती है।

**विरासत:**[`TiffOptions`](/slides/python-net/hi/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)

The TiffOptions type exposes the following members:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.export/tiffoptions/__init__/#) | Default constructor. |

## गुण

| गुण | विवरण |
| :- | :- |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/tiffoptions/warning_callback/) | एक वस्तु को लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी।<br/>            Read/write [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/tiffoptions/progress_callback/) | प्रतिशत में सहेजने की प्रगति अपडेट के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है।<br/>            See [`IProgressCallback`](/slides/python-net/hi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/tiffoptions/default_regular_font/) | जब स्रोत फ़ॉन्ट न मिले तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता या सेट करता है।<br/>            Read-write **str**. |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/tiffoptions/gradient_style/) | ग्रेडिएंट की दृश्य शैली को लौटाता या सेट करता है।<br/>            Read/write [`GradientStyle`](/slides/python-net/hi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/tiffoptions/skip_java_script_links/) | प्रस्तुति सहेजते समय जावा स्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, निर्दिष्ट करता है। <br/>            Read/write **bool**. डिफ़ॉल्ट मान **false** है। |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/tiffoptions/ink_options/) | निर्यात किए गए दस्तावेज़ में इंक ऑब्जेक्ट्स के स्वरूप को नियंत्रित करने वाले विकल्प प्रदान करता है।<br/>            Read-only [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/tiffoptions/show_hidden_slides/) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छुपी स्लाइडें शामिल होंगी या नहीं।<br/>            Default is `false`. |
| [`image_size`](/slides/python-net/hi/aspose.slides.export/tiffoptions/image_size/) | उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि के आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किए जाएंगे।<br/>            Read/write **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/hi/aspose.slides.export/tiffoptions/dpi_x/) | डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है।<br/>            Read/write **int**. |
| [`dpi_y`](/slides/python-net/hi/aspose.slides.export/tiffoptions/dpi_y/) | डॉट्स प्रति इंच में ऊर्ध्वाधर रिज़ॉल्यूशन निर्दिष्ट करता है।<br/>            Read/write **int**. |
| [`compression_type`](/slides/python-net/hi/aspose.slides.export/tiffoptions/compression_type/) | संपीड़न प्रकार को निर्दिष्ट करता है।<br/>            Read/write [`TiffCompressionTypes`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/hi/aspose.slides.export/tiffoptions/pixel_format/) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है।<br/>            Read/write [`ImagePixelFormat`](/slides/python-net/hi/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/hi/aspose.slides.export/tiffoptions/slides_layout_options/) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता या सेट करता है [`ISlidesLayoutOptions`](/slides/python-net/hi/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/hi/aspose.slides.export/tiffoptions/bw_conversion_mode/) | रंग छवि को काली और सफेद छवि में परिवर्तित करने के लिए एल्गोरिद्म निर्दिष्ट करता है।<br/>            यह विकल्प केवल तब लागू होगा जब [`TiffOptions.compression_type`](/slides/python-net/hi/aspose.slides.export/tiffoptions/compression_type) <br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes/CCITT4) या [`TiffCompressionTypes.CCITT3`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes/CCITT3) पर सेट हो<br/>            Read/write [`BlackWhiteConversionMode`](/slides/python-net/hi/aspose.slides.export/blackwhiteconversionmode).<br/>            Default is [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/hi/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |


### संबंधित देखें
* वर्ग [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)
* वर्ग [`TiffOptions`](/slides/python-net/hi/aspose.slides.export/tiffoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)