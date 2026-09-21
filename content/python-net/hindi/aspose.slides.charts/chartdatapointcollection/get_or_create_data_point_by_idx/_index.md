---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            यदि संग्रह में पहले से ही `index` इंडेक्स वाला डेटा पॉइंट मौजूद है तो यह डेटा पॉइंट वापस करता है।
            यदि संग्रह में डेटा पॉइंट `index`==N नहीं है
            (जब इस संग्रह में डेटा पॉइंटों की संख्या N से कम या बराबर हो)
            तो न्यून डेटा पॉइंट जोड़ता है और अंतिम (जिसका अनुरोधित इंडेक्स है) वापस करता है।
            उदाहरण के लिए, संग्रह के इंडेक्स {0, 1, 2} हैं, और अनुरोधित इंडेक्स 5 है।
            फिर मेथड न्यून डेटा पॉइंट जोड़ता है: {0, 1, 2, 3, 4, 5}. और इंडेक्स 5 वाला डेटा पॉइंट वापस करता है।

### वापसी

अनुरोधित इंडेक्स वाला डेटा पॉइंट वापस करता है.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इंडेक्स। |



### संबंधित देखें
* क्लास [`ChartDataPointCollection`](/slides/python-net/hi/aspose.slides.charts/chartdatapointcollection)
* क्लास [`IChartDataPoint`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)