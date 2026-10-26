---
title: StringChartValue class
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/stringchartvalue/
---
## StringChartValue क्लास

pptx प्रस्तुति दस्तावेज़ में स्ट्रिंग मान को दो तरीकों से संग्रहीत किया जा सकता है:
            1) चार्ट से संबंधित वर्कबुक की सेल/सेल्स में;
            2) एक लिटरल मान के रूप में।

**विरासत:**[`StringChartValue`](/slides/python-net/hi/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/hi/aspose.slides.charts/basechartvalue)

The StringChartValue type exposes the following members:

## गुण

| गुण | विवरण |
| :- | :- |
| [`data_source_type`](/slides/python-net/hi/aspose.slides.charts/stringchartvalue/data_source_type/) | निर्धारित करता है कि AsCell, AsCells, AsLiteralString या AsLiteralDouble <br/>            प्रॉपर्टी उतरावों में वास्तविक है या नहीं। अन्य शब्दों में यह Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है।<br/>            पढ़ें/लिखें [`DataSourceType`](/slides/python-net/hi/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/hi/aspose.slides.charts/stringchartvalue/data/) | Data ऑब्जेक्ट को लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **any**. |
| [`as_cells`](/slides/python-net/hi/aspose.slides.charts/stringchartvalue/as_cells/) | नल मान असाइन करना अनुमति नहीं है।<br/>            लौटाए जाने वाला मान हमेशा None नहीं होता।<br/>            पढ़ें/लिखें [`IChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/hi/aspose.slides.charts/stringchartvalue/as_literal_string/) | मूल स्ट्रिंग के रूप में मान को लौटाता है या सेट करता है।<br/>            पढ़ें/लिखें **str**. |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/hi/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | निर्दिष्ट सेल से मान सेट करता है। |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/hi/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | यदि DataSourceType प्रॉपर्टी DataSourceType.Worksheet है तो यह मेथड वर्कबुक में उन सेल्स का पता लौटाता है जो स्ट्रिंग डेटा का प्रतिनिधित्व करते हैं।<br/>            अन्यथा खाली स्ट्रिंग लौटाता है। |

### संबंधित देखें
* क्लास [`BaseChartValue`](/slides/python-net/hi/aspose.slides.charts/basechartvalue)
* क्लास [`StringChartValue`](/slides/python-net/hi/aspose.slides.charts/stringchartvalue)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)