---
title: SwfOptions class
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/swfoptions/
---
## SwfOptions क्लास

प्रस्तुति को Swf फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

**विरासत:**[`SwfOptions`](/slides/python-net/hi/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)

SwfOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides.export/swfoptions/__init__/#) | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`warning_callback`](/slides/python-net/hi/aspose.slides.export/swfoptions/warning_callback/) | वह ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियाँ प्राप्त करता है और निर्णय लेता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी।<br/>            पढ़ें/लिखें [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/hi/aspose.slides.export/swfoptions/progress_callback/) | प्रतिशत में सहेजने की प्रगति अद्यतन के लिए एक कॉलबैक ऑब्जेक्ट प्रस्तुत करता है।<br/>            देखें [`IProgressCallback`](/slides/python-net/hi/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides.export/swfoptions/default_regular_font/) | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को लौटाता या सेट करता है।<br/>            पढ़ें-लिखें **str**. |
| [`gradient_style`](/slides/python-net/hi/aspose.slides.export/swfoptions/gradient_style/) | ग्रेडिएंट की दृश्य शैली को लौटाता या सेट करता है।<br/>            पढ़ें/लिखें [`GradientStyle`](/slides/python-net/hi/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/hi/aspose.slides.export/swfoptions/skip_java_script_links/) | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना चाहिए या नहीं, यह निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **bool**. डिफ़ॉल्ट मान **false** है। |
| [`show_hidden_slides`](/slides/python-net/hi/aspose.slides.export/swfoptions/show_hidden_slides/) | जेनरेट किए गए दस्तावेज़ में छिपी हुई स्लाइड्स शामिल करनी चाहिए या नहीं, यह निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट `false` है। |
| [`compressed`](/slides/python-net/hi/aspose.slides.export/swfoptions/compressed/) | जेनरेट किए गए SWF दस्तावेज़ को संकुचित करना चाहिए या नहीं, यह निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट `true` है। |
| [`viewer_included`](/slides/python-net/hi/aspose.slides.export/swfoptions/viewer_included/) | जेनरेट किए गए SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल करना चाहिए या नहीं, यह निर्दिष्ट करता है।<br/>            डिफ़ॉल्ट `true` है। |
| [`show_page_border`](/slides/python-net/hi/aspose.slides.export/swfoptions/show_page_border/) | पृष्ठों के चारों ओर की बॉर्डर दिखानी चाहिए या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट true है। |
| [`show_full_screen`](/slides/python-net/hi/aspose.slides.export/swfoptions/show_full_screen/) | फ़ुलस्क्रीन बटन दिखाएँ/छिपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [`show_page_stepper`](/slides/python-net/hi/aspose.slides.export/swfoptions/show_page_stepper/) | पेज स्टेपर दिखाएँ/छिपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [`show_search`](/slides/python-net/hi/aspose.slides.export/swfoptions/show_search/) | खोज सेक्शन दिखाएँ/छिपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [`show_top_pane`](/slides/python-net/hi/aspose.slides.export/swfoptions/show_top_pane/) | पूरा टॉप पेन दिखाएँ/छिपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [`show_bottom_pane`](/slides/python-net/hi/aspose.slides.export/swfoptions/show_bottom_pane/) | निचला पेन दिखाएँ/छिपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [`show_left_pane`](/slides/python-net/hi/aspose.slides.export/swfoptions/show_left_pane/) | बाएँ पेन दिखाएँ/छिपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [`start_open_left_pane`](/slides/python-net/hi/aspose.slides.export/swfoptions/start_open_left_pane/) | खुले हुए बाएँ पेन के साथ शुरू करें। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है। |
| [`enable_context_menu`](/slides/python-net/hi/aspose.slides.export/swfoptions/enable_context_menu/) | संदर्भ मेनू सक्षम/अक्षम करें। डिफ़ॉल्ट true है। |
| [`logo_image_bytes`](/slides/python-net/hi/aspose.slides.export/swfoptions/logo_image_bytes/) | व्यूअर के शीर्ष दाएँ कोने में लोगो के रूप में प्रदर्शित होने वाली इमेज।<br/> इमेज 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो सही से नहीं दिख सकता। |
| [`logo_link`](/slides/python-net/hi/aspose.slides.export/swfoptions/logo_link/) | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता या सेट करता है।<br/> यह केवल तभी प्रभावी होता है जब [`SwfOptions.logo_image_bytes`](/slides/python-net/hi/aspose.slides.export/swfoptions/logo_image_bytes) निर्दिष्ट किया गया हो। |
| [`jpeg_quality`](/slides/python-net/hi/aspose.slides.export/swfoptions/jpeg_quality/) | JPEG इमेज की गुणवत्ता निर्धारित करता है।<br/> डिफ़ॉल्ट 95 है। |
| [`slides_layout_options`](/slides/python-net/hi/aspose.slides.export/swfoptions/slides_layout_options/) | प्रस्तुति [`ISlidesLayoutOptions`](/slides/python-net/hi/aspose.slides.export/islideslayoutoptions) निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता या सेट करता है।<br/> यह प्रॉपर्टी प्रकार [`HandoutLayoutingOptions`](/slides/python-net/hi/aspose.slides.export/handoutlayoutingoptions) के ऑब्जेक्ट को असाइन करने का समर्थन नहीं करता। |

### संबंधित देखें
* क्लास [`SaveOptions`](/slides/python-net/hi/aspose.slides.export/saveoptions)
* क्लास [`SwfOptions`](/slides/python-net/hi/aspose.slides.export/swfoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)