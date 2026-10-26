---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
यदि संग्रह में पहले से ही इंडेक्स `index` वाला डेटा पॉइंट मौजूद है तो वह इस डेटा पॉइंट को लौटाता है।  
यदि संग्रह में इंडेक्स `index`==N वाला डेटा पॉइंट नहीं है (जब इस संग्रह में डेटा पॉइंट्स की संख्या N से कम या बराबर हो) तो यह कमी वाले डेटा पॉइंट्स जोड़ता है और अंतिम डेटा पॉइंट को लौटाता है (जिसका अनुरोधित इंडेक्स है)।  
उदाहरण के लिए, संग्रह के इंडेक्स {0, 1, 2} हैं, और अनुरोधित इंडेक्स 5 है। तब मेथड कमी वाले डेटा पॉइंट्स जोड़ता है: {0, 1, 2, 3, 4, 5}। और इंडेक्स 5 वाला डेटा पॉइंट लौटाता है।

### रिटर्न्स

अनुरोधित इंडेक्स वाले डेटा पॉइंट को लौटाता है।



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| index | **int** | इंडेक्स। |



### देखें भी
* क्लास [`IChartDataPoint`](/slides/python-net/hi/aspose.slides.charts/ichartdatapoint)
* क्लास [`IChartDataPointCollection`](/slides/python-net/hi/aspose.slides.charts/ichartdatapointcollection)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)