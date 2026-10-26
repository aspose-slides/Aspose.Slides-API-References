---
title: IDataLabelFormat class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat क्लास

DataLabel के लिए स्वरूपण विकल्पों का प्रतिनिधित्व करता है।

IDataLabelFormat प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/) | पढ़ें/लिखें **bool**. |
| [`number_format`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/number_format/) | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है।<br/>            पढ़ें/लिखें **str**. |
| [`format`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/format/) | डेटा लेबल के फ़ॉर्मेट का प्रतिनिधित्व करता है।<br/>            केवल-पढ़ने योग्य [`IFormat`](/slides/python-net/hi/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/position/) | डेटा लेबल की स्थिति का प्रतिनिधित्व करता है।<br/>            पढ़ें/लिखें [`LegendDataLabelPosition`](/slides/python-net/hi/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_legend_key/) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। <br/>            यदि डेटा लेबल लेजेंड कुंजी दृश्यमान है तो True।<br/>            पढ़ें/लिखें **bool**. |
| [`show_value`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_value/) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। <br/>            True प्रतिशत मान को दर्शाता है। False छिपाने के लिए।<br/>            पढ़ें/लिखें **bool**. |
| [`show_category_name`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_category_name/) | निर्दिष्ट चार्ट के डेटा लेबल वर्ग नाम डिस्प्ले व्यवहार का प्रतिनिधित्व करता है।<br/>            चार्ट पर डेटा लेबल के लिये वर्ग नाम दिखाने हेतु True। False छिपाने के लिए।<br/>            पढ़ें/लिखें **bool**. |
| [`show_series_name`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_series_name/) | चार्ट पर डेटा लेबल के लिये श्रृंखला नाम डिस्प्ले व्यवहार को इंगित करने हेतु Boolean लौटाता है या सेट करता है। <br/>            श्रृंखला नाम दिखाने हेतु True। False छिपाने के लिए।<br/>            पढ़ें/लिखें **bool**. |
| [`show_percentage`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_percentage/) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। <br/>            True प्रतिशत मान को दर्शाता है। False छिपाने के लिए।<br/>            पढ़ें/लिखें **bool**. |
| [`show_bubble_size`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_bubble_size/) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। <br/>            True बबल आकार मान को दर्शाता है। False छिपाने के लिए।<br/>            पढ़ें/लिखें **bool**. |
| [`show_leader_lines`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_leader_lines/) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। <br/>            True लीडर लाइन्स को दर्शाता है। False छिपाने के लिए।<br/>            पढ़ें/लिखें **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा।<br/>            <br/>            यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट डेटा लेबलों का DataLabelCollection संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबलों के लिए ShowLabelAsDataCallout प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है।<br/>            इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी डेटा लेबलों के लिए DataLabelCollection संग्रह में ShowLabelAsDataCallout प्रॉपर्टी पर भी सेट हो जाता है।<br/>            (उदा. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" कारण सभी DataLabels[i].ShowLabelAsDataCallout बराबर val हो जाता है). |
| [`show_label_value_from_cell`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। <br/>            True सेल मान को दर्शाता है। False छिपाने के लिए।<br/>            पढ़ें/लिखें **bool**. |
| [`separator`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/separator/) | चार्ट पर डेटा लेबलों के लिये प्रयुक्त विभाजक को दर्शाने वाला Variant सेट या लौटाता है।<br/>            पढ़ें/लिखें **str**. |
| [`text_format`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/text_format/) |  |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/chart/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat/presentation/) |  |

### देखें
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)