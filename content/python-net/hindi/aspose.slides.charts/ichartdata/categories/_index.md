---
title: categories property
second_title: Aspose.Slides फ़ॉर पाइथन विया .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## श्रेणियों की संपत्ति
प्राथमिक श्रेणियाँ प्राप्त करता है (या दोनों प्राथमिक और द्वितीयक श्रेणियाँ यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) संपत्ति असत्य है)।
केवल-पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection).


### टिप्पणी

यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) संपत्ति असत्य है तो [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) संपत्ति None लौटाती है और इस [`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) संपत्ति में डेटा को प्राथमिक और द्वितीयक श्रृंखला दोनों के लिए उपयोग किया जाता है।
यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) संपत्ति सत्य है तो [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) संपत्ति में डेटा द्वितीयक श्रृंखला के लिए उपयोग किया जाता है और इस [`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) संपत्ति में डेटा प्राथमिक श्रृंखला के लिए उपयोग किया जाता है।

### परिभाषा:
```python
@property
def categories(self):
    ...
```


### देखें
* वर्ग [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)
* वर्ग [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)