---
title: number_format property
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format خاصية
يمثل سلسلة التنسيق لكائن DataLabels.
قراءة/كتابة **str**.

### ملاحظات

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل أو تعيين القيمة الافتراضية لخاصية NumberFormat للتسميات الجديدة في مجموعة DataLabelCollection. عندما يتم تعيين هذه الخاصية بقيمة، يتم أيضًا تعيين تلك القيمة لخاصية NumberFormat لجميع تسميات البيانات في مجموعة DataLabelCollection (على سبيل المثال "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" يؤدي إلى أن جميع DataLabels[i].NumberFormat تساوي val).

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
* فئة [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)