---
title: categories property
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## श्रेणियों गुण
प्राथमिक श्रेणियां प्राप्त करता है (या दोनों प्राथमिक और द्वितीयक श्रेणियां यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) गुण false है)। केवल-पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)।

### टिप्पणी
यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) गुण false है तो [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) गुण None लौटाता है और इस [`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) गुण में डेटा दोनों प्राथमिक और द्वितीयक श्रृंखला के लिए उपयोग होता है। यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) गुण true है तो [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) गुण में डेटा द्वितीयक श्रृंखला के लिए उपयोग होता है और इस [`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) गुण में डेटा प्राथमिक श्रृंखला के लिए उपयोग होता है।

### परिभाषा:
```python
@property
def categories(self):
    ...
```

### देखें
* क्लास [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)
* क्लास [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)