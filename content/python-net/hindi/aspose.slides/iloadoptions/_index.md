---
title: ILoadOptions class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iloadoptions/
---
## ILoadOptions क्लास

प्रस्तुति लोड करते समय अतिरिक्त विकल्प (जैसे स्वरूप या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।

ILoadOptions प्रकार निम्न सदस्य प्रदर्शित करता है:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`load_format`](/slides/python-net/hi/aspose.slides/iloadoptions/load_format/) | लोड होने वाली प्रस्तुति के स्वरूप को प्राप्त करता है या सेट करता है।<br/>            Read/write [`LoadFormat`](/slides/python-net/hi/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides/iloadoptions/default_regular_font/) | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाला नियमित फ़ॉन्ट प्राप्त करता है या सेट करता है।<br/>            Read-write **str**. |
| [`default_symbol_font`](/slides/python-net/hi/aspose.slides/iloadoptions/default_symbol_font/) | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाला सिम्बॉल फ़ॉन्ट प्राप्त करता है या सेट करता है।<br/>            Read-write **str**. |
| [`default_asian_font`](/slides/python-net/hi/aspose.slides/iloadoptions/default_asian_font/) | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाला एशियन फ़ॉन्ट प्राप्त करता है या सेट करता है।<br/>            Read-write **str**. |
| [`password`](/slides/python-net/hi/aspose.slides/iloadoptions/password/) | पासवर्ड प्राप्त करता है या सेट करता है।<br/>            Read-write **str**. |
| [`only_load_document_properties`](/slides/python-net/hi/aspose.slides/iloadoptions/only_load_document_properties/) | यह प्रॉपर्टी तब मायने रखती है जब प्रस्तुति फ़ाइल पासवर्ड से सुरक्षित हो।<br/>            true मान का अर्थ है कि केवल दस्तावेज़ गुणों को एन्क्रिप्टेड प्रस्तुति फ़ाइल से लोड किया जाना चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए।<br/>            false मान का अर्थ है कि संपूर्ण एन्क्रिप्टेड प्रस्तुति को सही पासवर्ड का उपयोग करके लोड किया जाना चाहिए।<br/>            यदि प्रस्तुति एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है।<br/>            यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो दस्तावेज़ गुण लोड नहीं किए जा सकते और एक अपवाद फेंका जाएगा।<br/>            Read-write **bool**. |
| [`warning_callback`](/slides/python-net/hi/aspose.slides/iloadoptions/warning_callback/) | एक ऑब्जेक्ट प्राप्त करता है या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग <br/>            प्रक्रिया जारी रहेगी या रद्द की जाएगी।<br/>            Read/write [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/hi/aspose.slides/iloadoptions/blob_management_options/) | विकल्पों का प्रतिनिधित्व करता है जिन्हें बाइनरी लार्ज ऑब्जेक्ट्स (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के लिए उपयोग किया जा सकता है,<br/>            जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। ये विकल्प एक विशिष्ट वातावरण या आवश्यकताओं के लिए सबसे अच्छा प्रदर्शन/मेमोरी खपत अनुपात स्थापित करने हेतु नियत हैं।<br/>            बाइनरी लार्ज ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक एकल इकाई के रूप में संग्रहीत होता है - यानी BLOB ऑडियो, वीडियो या स्वयं प्रस्तुति हो सकता है। |
| [`document_level_font_sources`](/slides/python-net/hi/aspose.slides/iloadoptions/document_level_font_sources/) | प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्टों के स्रोत निर्दिष्ट करता है।<br/>            ये फ़ॉन्ट प्रस्तुति के पूरे जीवनकाल में उपलब्ध रहते हैं और अन्य प्रस्तुतियों के साथ साझा नहीं होते। |
| [`interruption_token`](/slides/python-net/hi/aspose.slides/iloadoptions/interruption_token/) | विच्छेदन अनुरोधों की निगरानी के लिए टोकन।<br/>            <br/>            यह टोकन पूरे [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) उदाहरण के जीवनकाल को प्रबंधित करता है। कोई भी लंबी चलने वाली प्रक्रिया, जैसे प्रस्तुति <br/>            लोड करना या सहेजना, [`IInterruptionTokenSource.interrupt`](/slides/python-net/hi/aspose.slides/iinterruptiontokensource/interrupt) मेथड को कॉल करके [`IInterruptionTokenSource`](/slides/python-net/hi/aspose.slides/iinterruptiontokensource) द्वारा बाधित की जाएगी। |
| [`resource_loading_callback`](/slides/python-net/hi/aspose.slides/iloadoptions/resource_loading_callback/) | एक कॉलबैक इंटरफ़ेस प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग को प्रबंधित करता है।<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/hi/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/hi/aspose.slides/iloadoptions/spreadsheet_options/) | ऐसे विकल्पों का प्रतिनिधित्व करता है जिन्हें अतिरिक्त स्प्रेडशीट व्यवहार निर्दिष्ट करने के लिए उपयोग किया जा सकता है। |
| [`default_text_language`](/slides/python-net/hi/aspose.slides/iloadoptions/default_text_language/) | प्रस्तुति पाठ के लिए डिफ़ॉल्ट भाषा प्राप्त करता है या सेट करता है।<br/>             Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/hi/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | निर्धारित करता है कि प्रस्तुति लोड होते समय Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं।<br/>            <br/>एम्बेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:<br/><br/><br/>* VBA प्रोजेक्ट [`IPresentation.vba_project`](/slides/python-net/hi/aspose.slides/ipresentation/vba_project)<br/>* OLE ऑब्जेक्ट एम्बेडेड डेटा [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX कंट्रोल बाइनरी डेटा [`IControl.active_x_control_binary`](/slides/python-net/hi/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Read/write **bool**. |


### देखें भी
* मॉड्युल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)