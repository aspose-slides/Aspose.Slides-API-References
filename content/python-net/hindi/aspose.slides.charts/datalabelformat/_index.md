---
title: DataLabelFormat class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat क्लास

डेटा लेबल के फ़ॉर्मेट विकल्पों का प्रतिनिधित्व करता है।

**Inheritance:**[`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat) → [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)

DataLabelFormat प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/) | पढ़ने/लिखने योग्य **bool**. |
| [`number_format`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/number_format/) | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग को दर्शाता है.<br/>पढ़ने/लिखने योग्य **str**. |
| [`format`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/format/) | डेटा लेबल के फ़ॉर्मेट को दर्शाता है.<br/>केवल पढ़ने योग्य [`IFormat`](/slides/python-net/hi/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/position/) | डेटा लेबल की स्थिति को दर्शाता है.<br/>पढ़ने/लिखने योग्य [`LegendDataLabelPosition`](/slides/python-net/hi/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_legend_key/) | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शित व्यवहार को दर्शाता है.<br/>डेटा लेबल लेजेंड कुंजी दृश्यमान होने पर True.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`show_value`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_value/) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शित व्यवहार को दर्शाता है.<br/>True प्रतिशत मान दिखाता है. False छिपाने के लिए.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`show_category_name`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_category_name/) | निर्दिष्ट चार्ट के डेटा लेबल वर्ग नाम प्रदर्शित व्यवहार को दर्शाता है.<br/>डेटा लेबल पर वर्ग नाम दिखाने के लिए True. छिपाने के लिए False.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`show_series_name`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_series_name/) | चार्ट पर डेटा लेबल्स के लिए श्रृंखला नाम प्रदर्शित व्यवहार को दर्शाने वाला Boolean लौटाता या सेट करता है.<br/>श्रृंखला नाम दिखाने के लिए True. छिपाने के लिए False.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`show_percentage`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_percentage/) | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शित व्यवहार को दर्शाता है.<br/>True प्रतिशत मान दिखाता है. False छिपाने के लिए.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`show_bubble_size`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_bubble_size/) | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शित व्यवहार को दर्शाता है.<br/>True बबल आकार मान दिखाता है. False छिपाने के लिए.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`show_leader_lines`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_leader_lines/) | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स प्रदर्शित व्यवहार को दर्शाता है.<br/>True लीडर लाइन्स दिखाता है. False छिपाने के लिए.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`show_label_value_from_cell`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_label_value_from_cell/) | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शित व्यवहार को दर्शाता है.<br/>True सेल मान दिखाता है. False छिपाने के लिए.<br/>पढ़ने/लिखने योग्य **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/show_label_as_data_callout/) | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा.<br/><br/>यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection संग्रह है जो डेटा लेबल्स का संग्रह है, तो यह<br/>प्रॉपर्टी नई डेटा लेबल्स के लिए ShowLabelAsDataCallout प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है.<br/>इस प्रॉपर्टी को मान के साथ सेट करना सभी डेटा लेबल्स में ShowLabelAsDataCallout प्रॉपर्टी को भी उसी मान पर सेट करता है<br/>(उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" सभी DataLabels[i].ShowLabelAsDataCallout को val के बराबर बनाता है). |
| [`separator`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/separator/) | चार्ट पर डेटा लेबल्स के लिए उपयोग किए जाने वाले विभाजक को दर्शाने वाला Variant सेट या लौटाता है.<br/>पढ़ने/लिखने योग्य **str**. |
| [`text_format`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/text_format/) | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है.<br/>केवल पढ़ने योग्य [`IChartTextFormat`](/slides/python-net/hi/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/chart/) | चार्ट लौटाता है.<br/>केवल पढ़ने योग्य [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides.charts/datalabelformat/presentation/) |  |

### संबंधित देखें
* क्लास [`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat)
* क्लास [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)