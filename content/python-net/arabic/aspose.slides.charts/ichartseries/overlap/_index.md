---
title: overlap property
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap خاصية
يحدد كيف تتداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). 
            هذه ليست الخاصية فقط لهذه series ولكن لجميع series في parent series group. 
            إنها إسقاط للخاصية المناسبة في parent series group، وبالتالي هذه الخاصية للقراءة فقط.
            لتغيير القيمة، استخدم الخاصية ParentSeriesGroup.Overlap للقراءة/الكتابة.
            للقراءة فقط **int**.


### ملاحظات

تحدد Overlap درجة التداخل أو الفارق بين bars و columns كنسبة مئوية من عرضها:
            - -100%: أقصى مسافة (bars مفصولة تمامًا).
            - 0%: يتم وضع Bars جنبًا إلى جنب بدون تداخل أو فراغ.
            - 100%: أقصى تداخل (bars تتداخل تمامًا مع بعضها).
            هذا إسقاط للخاصية ParentSeriesGroup.Overlap.

### التعريف:
```python
@property
def overlap(self):
    ...
```


### انظر أيضًا
* فئة [`IChartSeries`](/slides/python-net/ar/aspose.slides.charts/ichartseries)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)