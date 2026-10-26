---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint क्लास

Represents series data point.

The IChartDataPoint type exposes the following members:

## गुण

| प्रॉपर्टी | विवरण |
| :- | :- |
| [`x_value`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/x_value/) | चार्ट डेटा पॉइंट का x मान लौटाता है।<br/>            केवल-पढ़नेयोग्य [`IStringOrDoubleChartValue`](/slides/python-net/hi/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/y_value/) | चार्ट डेटा पॉइंट का y मान लौटाता है।<br/>            केवल-पढ़नेयोग्य [`IDoubleChartValue`](/slides/python-net/hi/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/bubble_size/) | चार्ट डेटा पॉइंट का बबल आकार लौटाता है।<br/>            केवल-पढ़नेयोग्य [`IDoubleChartValue`](/slides/python-net/hi/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/value/) | चार्ट डेटा पॉइंट का मान लौटाता है।<br/>            केवल-पढ़नेयोग्य [`IDoubleChartValue`](/slides/python-net/hi/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/size_value/) | चार्ट डेटा पॉइंट का आकार मान लौटाता है।<br/>            Treemap और Sunburst चार्ट के साथ उपयोग किया जाता है। <br/>            केवल-पढ़नेयोग्य [`IDoubleChartValue`](/slides/python-net/hi/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/color_value/) | चार्ट डेटा पॉइंट का रंग मान लौटाता है।<br/>            Map चार्ट के साथ उपयोग किया जाता है। <br/>            केवल-पढ़नेयोग्य [`IDoubleChartValue`](/slides/python-net/hi/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Custom मान प्रकार के मामले में श्रृंखला त्रुटि बार मान का प्रतिनिधित्व करता है।<br/>            केवल-पढ़नेयोग्य [`IErrorBarsCustomValues`](/slides/python-net/hi/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/label/) | चार्ट डेटा पॉइंट के लेबल का प्रतिनिधित्व करता है।<br/>            केवल-पढ़नेयोग्य [`IDataLabel`](/slides/python-net/hi/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | यह निर्दिष्ट करता है कि बबल्स पर 3-डी असर लागू किया गया है।<br/>            पढ़ें/लिखें **bool**. |
| [`explosion`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/explosion/) | यह निर्दिष्ट करता है कि डेटा पॉइंट को पाई के केंद्र से कितना स्थानांतरित किया जाना है।<br/>            पढ़ें/लिखें **int**. |
| [`format`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/format/) | फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है।<br/>            पढ़ें/लिखें [`IFormat`](/slides/python-net/hi/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/marker/) | डेटा मार्कर निर्दिष्ट करता है।<br/>            केवल-पढ़नेयोग्य [`IMarker`](/slides/python-net/hi/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | इस सूची के चार्ट प्रकार के मामले में संबंधित लीजेंड एंट्री की प्रॉपर्टीज़:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            केवल-पढ़नेयोग्य [`ILegendEntryProperties`](/slides/python-net/hi/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/set_as_total/) | डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू। |
| [`invert_if_negative`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | यदि मान नकारात्मक हो तो डेटा पॉइंट अपने रंग उलट देगा, यह निर्दिष्ट करता है।<br/>            पढ़ें/लिखें **bool**. |
| [`data_point_levels`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/data_point_levels/) | डेटा पॉइंट स्तरों का कंटेनर लौटाता है। Treeamp और Sunburst श्रृंखला के लिए लागू।<br/>            डेटा पॉइंट स्तर इंडेक्सिंग शून्य-आधारित है। |
| [`index`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/index/) | निर्धारित करता है कि इस डेटा पॉइंट को पैरेंट के कौन से चाइल्ड कलेक्शन पर लागू किया जाए।<br/>            पढ़ें **int**. |
| [`actual_x`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`remove(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/remove/#) | डेटा पॉइंट को चार्ट श्रृंखला से हटाता है। |
| [`get_automatic_data_point_color(self)`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | श्रृंखला सूचकांक, डेटा पॉइंट सूचकांक, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट शैली के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। <br/>            यदि FillType NotDefined के बराबर हो तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |


### देखें भी
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)