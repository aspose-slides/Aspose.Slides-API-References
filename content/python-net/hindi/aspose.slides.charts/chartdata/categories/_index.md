---
title: categories property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/categories/
weight: 70
---
## श्रेणियाँ प्रॉपर्टी
प्राथमिक श्रेणियों को प्राप्त करता है (या यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) प्रॉपर्टी false है तो प्राथमिक और द्वितीयक दोनों श्रेणियों को)। केवल-पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection).

### टिप्पणी

यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) प्रॉपर्टी false है तो [`ChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories) प्रॉपर्टी None लौटाती है और इस [`ChartData.categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories) प्रॉपर्टी का डेटा प्राथमिक तथा द्वितीयक दोनों सीरीज़ के लिए उपयोग किया जाता है। यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) प्रॉपर्टी true है तो [`ChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories) प्रॉपर्टी का डेटा द्वितीयक सीरीज़ के लिए उपयोग किया जाता है और इस [`ChartData.categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories) प्रॉपर्टी का डेटा प्राथमिक सीरीज़ के लिए उपयोग किया जाता है।

### परिभाषा:
```python
@property
def categories(self):
    ...
```

### देखें
* क्लास [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* क्लास [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)