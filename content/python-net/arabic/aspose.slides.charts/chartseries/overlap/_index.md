---
title: overlap property
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## خاصية التراكب
يحدد مقدار تراكب الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%).
            هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية.
            إنها إسقاط للخاصية المناسبة في مجموعة السلاسل الأصلية، وبالتالي هذه الخاصية قراءة فقط.
            لتغيير القيمة، استخدم خاصية **ParentSeriesGroup.Overlap** قراءة/كتابة.
            قراءة فقط **int**.


### ملاحظات

التراكب يحدد درجة التراكب أو التباعد بين الأشرطة والأعمدة كنسبة مئوية من عرضها:
            - -100%: أقصى تباعد (الأشرطة منفصلة تمامًا).
            - 0%: توضع الأشرطة جنبًا إلى جنب دون تراكب أو تباعد.
            - 100%: أقصى تراكب (الأشرطة تتراكب تمامًا مع بعضها).
            هذا إسقاط للخاصية **ParentSeriesGroup.Overlap**.

### التعريف:
```python
@property
def overlap(self):
    ...
```


### انظر أيضًا
* فئة [`ChartSeries`](/slides/python-net/ar/aspose.slides.charts/chartseries)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)