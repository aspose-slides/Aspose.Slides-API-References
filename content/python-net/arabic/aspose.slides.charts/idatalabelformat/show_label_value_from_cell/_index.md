---
title: show_label_value_from_cell property
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell الخاصية
يمثل سلوك عرض قيمة خلية تسمية البيانات لمخطط محدد. 
            True يعرض قيمة الخلية. False لإخفائها.
            قراءة/كتابة **bool**.

### ملاحظات

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على القيمة الافتراضية أو تضعها لخاصية ShowLabelValueFromCell للتسميات الجديدة في مجموعة DataLabelCollection. تعيين هذه الخاصية بقيمة يضع هذه القيمة أيضًا لخاصية ShowLabelValueFromCell لجميع تسميات البيانات في مجموعة DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" سبب أن تكون جميع DataLabels[i].ShowLabelValueFromCell مساوية لـ val).

### التعريف:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### راجع أيضًا
* فئة [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)