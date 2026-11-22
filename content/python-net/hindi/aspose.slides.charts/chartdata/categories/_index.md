---
title: categories property
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/categories/
weight: 80
---
## श्रेणियों प्रॉपर्टी
प्राथमिक श्रेणियों (या दोनों प्राथमिक और द्वितीयक श्रेणियां 
            यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) प्रॉपर्टी false है) को प्राप्त करता है।
            केवल-पठन [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)।

### टिप्पणियाँ
यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) प्रॉपर्टी false है तो [`ChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories) 
            प्रॉपर्टी None लौटाती है और इस [`ChartData.categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories) प्रॉपर्टी में डेटा दोनों प्राथमिक 
            और द्वितीयक श्रृंखलाओं के लिए उपयोग किया जाता है।
            यदि [`ChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/use_secondary_categories) प्रॉपर्टी true है तो [`ChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/secondary_categories) 
            प्रॉपर्टी में डेटा द्वितीयक श्रृंखला के लिए उपयोग किया जाता है और इस [`ChartData.categories`](/slides/python-net/hi/aspose.slides.charts/chartdata/categories) प्रॉपर्टी में डेटा 
            प्राथमिक श्रृंखला के लिए उपयोग किया जाता है।

### परिभाषा:
```python
@property
def categories(self):
    ...
```

### देखें
* वर्ग [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* वर्ग [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)