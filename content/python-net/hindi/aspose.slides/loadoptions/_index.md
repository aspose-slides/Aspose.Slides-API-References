---
title: LoadOptions class
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/loadoptions/
---
## LoadOptions क्लास

प्रेजेंटेशन लोड करने के समय अतिरिक्त विकल्प (जैसे फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।

LoadOptions प्रकार निम्न सदस्यों को उजागर करता है:

## कंस्ट्रक्टर्स

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides/loadoptions/__init__/#) | Creates new default load options. |
| [`__init__(self, load_format)`](/slides/python-net/hi/aspose.slides/loadoptions/__init__/#loadformat) | Creates new load options. |

## गुण

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/hi/aspose.slides/loadoptions/load_format/) | लोड की जाने वाली प्रेजेंटेशन के फ़ॉर्मेट को प्राप्त या सेट करता है।<br/>            Read/write [`LoadFormat`](/slides/python-net/hi/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/hi/aspose.slides/loadoptions/default_regular_font/) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाला नियमित फ़ॉन्ट प्राप्त या सेट करता है।<br/>            Read/write **str**. |
| [`default_symbol_font`](/slides/python-net/hi/aspose.slides/loadoptions/default_symbol_font/) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाला सिम्बोल फ़ॉन्ट प्राप्त या सेट करता है।<br/>            Read/write **str**. |
| [`default_asian_font`](/slides/python-net/hi/aspose.slides/loadoptions/default_asian_font/) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाला एशियन फ़ॉन्ट प्राप्त या सेट करता है।<br/>            Read/write **str**. |
| [`password`](/slides/python-net/hi/aspose.slides/loadoptions/password/) | पासवर्ड प्राप्त या सेट करता है।<br/>            Read/write **str**. |
| [`only_load_document_properties`](/slides/python-net/hi/aspose.slides/loadoptions/only_load_document_properties/) | यदि प्रेजेंटेशन फ़ाइल पासवर्ड से सुरक्षित है तो यह प्रॉपर्टी अर्थपूर्ण होती है।<br/>            true मान का अर्थ है कि केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रेजेंटेशन फ़ाइल से लोड किए जाएँ और पासवर्ड को अनदेखा किया जाए।<br/>            false मान का अर्थ है कि पूरी एन्क्रिप्टेड प्रेजेंटेशन को सही पासवर्ड का उपयोग करके लोड किया जाए।<br/>            यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है।<br/>            यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो<br/>            दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद फेंका जाएगा।<br/>            Read/write **bool**. |
| [`warning_callback`](/slides/python-net/hi/aspose.slides/loadoptions/warning_callback/) | एक ऑब्जेक्ट प्राप्त या सेट करता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या बंद हो जाएगी।<br/>            Read/write [`IWarningCallback`](/slides/python-net/hi/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/hi/aspose.slides/loadoptions/blob_management_options/) | विकल्पों को प्रस्तुत करता है जिन्हें बाइनरी लार्ज ऑब्जेक्ट्स (BLOBs) के हेंडलिंग व्यवहार को प्रबंधित करने के लिए उपयोग किया जा सकता है,<br/>            जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। ये विकल्प एक विशेष पर्यावरण या आवश्यकताओं के लिए सर्वश्रेष्ठ प्रदर्शन/मेमोरी उपभोग अनुपात निर्धारित करने के लिए अभिप्रेत हैं।<br/>            बाइनरी लार्ज ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक ही इकाई के रूप में संग्रहीत होता है - अर्थात् BLOB ऑडियो, वीडियो या प्रेजेंटेशन स्वयं हो सकता है। |
| [`document_level_font_sources`](/slides/python-net/hi/aspose.slides/loadoptions/document_level_font_sources/) | प्रेजेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है।<br/>            ये फ़ॉन्ट्स प्रेजेंटेशन के पूरे जीवनकाल में उपलब्ध रहते हैं और अन्य प्रेजेंटेशनों के साथ साझा नहीं होते। |
| [`interruption_token`](/slides/python-net/hi/aspose.slides/loadoptions/interruption_token/) | इंटरप्शन अनुरोधों की निगरानी के लिए टोकन।<br/>            <br/>            यह टोकन पूरे [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) इंस्टेंस के जीवनकाल को प्रबंधित करता है। कोई भी लंबी अवधि की ऑपरेशन, जैसे प्रेजेंटेशन लोड करना या सहेजना, [`InterruptionTokenSource.interrupt`](/slides/python-net/hi/aspose.slides/interruptiontokensource/interrupt) मेथड को कॉल करके [`InterruptionTokenSource`](/slides/python-net/hi/aspose.slides/interruptiontokensource) द्वारा बाधित की जाएगी। |
| [`resource_loading_callback`](/slides/python-net/hi/aspose.slides/loadoptions/resource_loading_callback/) | एक कॉलबैक इंटरफ़ेस प्राप्त या सेट करता है जो बाहरी संसाधनों के लोडिंग का प्रबंधन करता है।<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/hi/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/hi/aspose.slides/loadoptions/spreadsheet_options/) | स्प्रेडशीट्स के लिए विकल्प प्राप्त करता है। उदाहरण के लिए, ये विकल्प चार्ट्स के फ़ॉर्मूला गणना को प्रभावित करते हैं। |
| [`default_text_language`](/slides/python-net/hi/aspose.slides/loadoptions/default_text_language/) | प्रेजेंटेशन टेक्स्ट के लिए डिफ़ॉल्ट भाषा प्राप्त या सेट करता है।<br/>             Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/hi/aspose.slides/loadoptions/delete_embedded_binary_objects/) | निर्धारित करता है कि प्रेजेंटेशन लोड करने के दौरान Aspose.Slides सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं।<br/>            <br/>एम्बेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/hi/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/hi/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Read/write **bool**. |


### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)