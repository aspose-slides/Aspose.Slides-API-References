---
title: ITiffOptions class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/itiffoptions/
---
## ITiffOptions वर्ग

प्रदर्शन को TIFF स्वरूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

ITiffOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`image_size`](/slides/python-net/hi/aspose.slides.export/itiffoptions/image_size/) | उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किया जाएगा।<br/>            पढ़ें/लिखें [`Size`](/slides/python-net/hi/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/hi/aspose.slides.export/itiffoptions/dpi_x/) | डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`dpi_y`](/slides/python-net/hi/aspose.slides.export/itiffoptions/dpi_y/) | डॉट्स प्रति इंच में लंबवत रिज़ॉल्यूशन निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **int**. |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/itiffoptions/show_hidden_slides/) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइडें शामिल होंगी या नहीं।<br/>            डिफ़ॉल्ट `false` है। |
| [`compression_type`](/slides/python-net/hi/aspose.slides.export/itiffoptions/compression_type/) | संपीड़न प्रकार निर्दिष्ट करता है।<br/>            पढ़ें/लिखें [`TiffCompressionTypes`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/hi/aspose.slides.export/itiffoptions/pixel_format/) | उत्पन्न छवियों के लिये पिक्सेल प्रारूप निर्दिष्ट करता है।<br/>            पढ़ें/लिखें [`ImagePixelFormat`](/slides/python-net/hi/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/hi/aspose.slides.export/itiffoptions/slides_layout_options/) | प्रस्तुति निर्यात करते समय स्लाइडों को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](/slides/python-net/hi/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/hi/aspose.slides.export/itiffoptions/bw_conversion_mode/) | रंगीन छवि को काली और सफ़ेद छवि में परिवर्तित करने के लिए एल्गोरिद्म निर्दिष्ट करता है।<br/>            यह विकल्प केवल तभी लागू होगा जब [`ITiffOptions.compression_type`](/slides/python-net/hi/aspose.slides.export/itiffoptions/compression_type) <br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes/CCITT4) या [`TiffCompressionTypes.CCITT3`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes/CCITT3) पर सेट हो<br/>            पढ़ें/लिखें [`BlackWhiteConversionMode`](/slides/python-net/hi/aspose.slides.export/blackwhiteconversionmode).<br/>            डिफ़ॉल्ट [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/hi/aspose.slides.export/blackwhiteconversionmode/DEFAULT) है। |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/itiffoptions/ink_options/) | निर्यातित दस्तावेज़ में इंक ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है।<br/>            केवल-पढ़ने योग्य [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)