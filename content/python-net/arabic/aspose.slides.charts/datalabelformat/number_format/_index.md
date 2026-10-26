---
title: number_format property
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format خاصية
يمثل سلسلة التنسيق لكائن DataLabels.
            قراءة/كتابة **str**.

### ملاحظات

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من ملصقات البيانات، فإن هذه
            الخاصية تحصل أو تضبط القيمة الافتراضية لخاصية NumberFormat للملصقات الجديدة
            في مجموعة DataLabelCollection.
            عند ضبط هذه الخاصية بقيمة، يتم أيضًا ضبط تلك القيمة لخاصية NumberFormat لجميع ملصقات البيانات في مجموعة DataLabelCollection
            (مثال: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" يجعل جميع DataLabels[i].NumberFormat تساوي val).

### التعريف:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### انظر أيضًا
* فئة [`DataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/datalabelformat)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)