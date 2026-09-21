---
title: MarkdownSaveOptions class
second_title: Aspose.Slides for Python के द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions वर्ग

प्रस्तुति को मार्कडाउन में सहेजने के तरीके को नियंत्रित करने वाले विकल्पों का प्रतिनिधित्व करता है।

**विरासत:**[`MarkdownSaveOptions`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)

The MarkdownSaveOptions type exposes the following members:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## गुण

| गुण | विवरण |
| :- | :- |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/warning_callback/) | एक ऑब्जेक्ट लौटाता है या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी।<br/> पढ़ें/लिखें [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/progress_callback/) | प्रतिशत में प्रगति अद्यतन सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है।<br/> देखें [`IProgressCallback`](/slides/python-net/hi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/default_regular_font/) | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है।<br/> पढ़ें-लिखें **str**. |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/gradient_style/) | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है।<br/> पढ़ें/लिखें [`GradientStyle`](/slides/python-net/hi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | प्रस्तुति सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है।<br/> पढ़ें/लिखें **bool**. डिफ़ॉल्ट मान **false** है. |
| [`export_type`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/export_type/) | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विनिर्देश निर्दिष्ट करता है।<br/> डिफ़ॉल्ट `TextOnly`. |
| [`base_path`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/base_path/) | संसाधनों वाले दस्तावेज़ को सहेजने के लिए आधार पथ निर्दिष्ट करता है।<br/> डिफ़ॉल्ट एप्लिकेशन की वर्तमान निर्देशिका है. |
| [`images_save_folder_name`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | छवियों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है।<br/> डिफ़ॉल्ट `Images`. |
| [`new_line_type`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/new_line_type/) | निर्धारित करता है कि निर्मित दस्तावेज़ में नई पंक्तियाँ \\r(Macintosh) या \\n(Unix) या \\r\\n(Windows) होनी चाहिए या नहीं।<br/> डिफ़ॉल्ट `Unix`. |
| [`show_comments`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/show_comments/) | निर्धारित करता है कि निर्मित दस्तावेज़ में टिप्पणियाँ दिखनी चाहिए या नहीं।<br/> डिफ़ॉल्ट `false`. |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | निर्धारित करता है कि निर्मित दस्तावेज़ में छिपी स्लाइडें शामिल हों या नहीं।<br/> डिफ़ॉल्ट `false`. |
| [`show_slide_number`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/show_slide_number/) | निर्धारित करता है कि निर्मित दस्तावेज़ में प्रत्येक स्लाइड का नंबर दिखना चाहिए या नहीं।<br/> डिफ़ॉल्ट `false`. |
| [`flavor`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/flavor/) | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विनिर्देश निर्दिष्ट करता है।<br/> डिफ़ॉल्ट `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/slide_number_format/) | मार्कडाउन आउटपुट में स्लाइड नंबर हेडर के लिए उपयोग होने वाली फ़ॉर्मेट स्ट्रिंग को प्राप्त करता है या सेट करता है।<br/> फ़ॉर्मेट में "{0}" प्लेसहोल्डर शामिल होना चाहिए, जिसे निर्यात के दौरान स्लाइड इंडेक्स से बदला जाएगा।<br/> उदाहरण: "# Slide {0}" उत्पन्न करेगा "# Slide 1", "# Slide 2", आदि. |
| [`handle_repeated_spaces`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | यदि `true` पर सेट किया जाता है, तो अंतिम मार्कडाउन आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटा देता है।<br/> डिफ़ॉल्ट `false`. |

### संबंधित देखें
* वर्ग [`MarkdownSaveOptions`](/slides/python-net/hi/aspose.slides.export/markdownsaveoptions)
* वर्ग [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)