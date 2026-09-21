---
title: ITiffOptions class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/itiffoptions/
---
## ITiffOptions क्लास

एक प्रस्तुति को TIFF प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

ITiffOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`image_size`](/slides/python-net/hi/aspose.slides.export/itiffoptions/image_size/) | उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है।<br/> डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि का आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किया जाएगा।<br/> पढ़ें/लिखें **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/hi/aspose.slides.export/itiffoptions/dpi_x/) | डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन निर्दिष्ट करता है।<br/> पढ़ें/लिखें **int**. |
| [`dpi_y`](/slides/python-net/hi/aspose.slides.export/itiffoptions/dpi_y/) | डॉट्स प्रति इंच में लंबवत रेज़ोल्यूशन निर्दिष्ट करता है।<br/> पढ़ें/लिखें **int**. |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/itiffoptions/show_hidden_slides/) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइडें शामिल होनी चाहिए या नहीं।<br/> डिफ़ॉल्ट `false` है। |
| [`compression_type`](/slides/python-net/hi/aspose.slides.export/itiffoptions/compression_type/) | कम्प्रेशन प्रकार निर्दिष्ट करता है।<br/> पढ़ें/लिखें [`TiffCompressionTypes`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/hi/aspose.slides.export/itiffoptions/pixel_format/) | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है।<br/> पढ़ें/लिखें [`ImagePixelFormat`](/slides/python-net/hi/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/hi/aspose.slides.export/itiffoptions/slides_layout_options/) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](/slides/python-net/hi/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/hi/aspose.slides.export/itiffoptions/bw_conversion_mode/) | रंगीन छवि को काली और सफ़ेद छवि में बदलने के एल्गोरिद्म को निर्दिष्ट करता है।<br/> यह विकल्प केवल तभी लागू होगा जब [`ITiffOptions.compression_type`](/slides/python-net/hi/aspose.slides.export/itiffoptions/compression_type) <br/> [`TiffCompressionTypes.CCITT4`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes/CCITT4) या [`TiffCompressionTypes.CCITT3`](/slides/python-net/hi/aspose.slides.export/tiffcompressiontypes/CCITT3) पर सेट हो<br/> पढ़ें/लिखें [`BlackWhiteConversionMode`](/slides/python-net/hi/aspose.slides.export/blackwhiteconversionmode).<br/> डिफ़ॉल्ट [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/hi/aspose.slides.export/blackwhiteconversionmode/DEFAULT) है। |
| [`ink_options`](/slides/python-net/hi/aspose.slides.export/itiffoptions/ink_options/) | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है।<br/> केवल-पढ़ना [`IInkOptions`](/slides/python-net/hi/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |


### देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)