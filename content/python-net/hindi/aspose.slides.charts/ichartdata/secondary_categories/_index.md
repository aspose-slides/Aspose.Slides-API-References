---
title: secondary_categories property
second_title: Aspose.Slides Python के लिये .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories प्रॉपर्टी
यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) प्रॉपर्टी true है तो द्वितीयक श्रेणियां प्राप्त करता है।
केवल पढ़ने योग्य [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)।

### टिप्पणियाँ

यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) प्रॉपर्टी false है तो यह [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) 
            प्रॉपर्टी None वापस करती है और [`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) प्रॉपर्टी में डेटा प्राथमिक 
            और द्वितीयक श्रृंखला दोनों के लिए उपयोग किया जाता है।
            यदि [`IChartData.use_secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/use_secondary_categories) प्रॉपर्टी true है तो डेटा 
            इस [`IChartData.secondary_categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/secondary_categories) प्रॉपर्टी में द्वितीयक श्रृंखला के लिए उपयोग किया जाता है और डेटा 
            इस [`IChartData.categories`](/slides/python-net/hi/aspose.slides.charts/ichartdata/categories) प्रॉपर्टी में प्राथमिक श्रृंखला के लिए उपयोग किया जाता है।

### परिभाषा:
```python
@property
def secondary_categories(self):
    ...
```

### देखें भी
* क्लास [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)
* क्लास [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)