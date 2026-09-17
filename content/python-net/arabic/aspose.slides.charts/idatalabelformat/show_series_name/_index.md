---
title: show_series_name property
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name خاصية
تُرجع أو تُعيّن قيمة منطقية لتحديد سلوك عرض اسم السلسلة لتسميات البيانات على الرسم البياني. 
            True لإظهار اسم السلسلة. False لإخفائه.
            قراءة/كتابة **bool**.


### ملاحظات

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            الخاصية تحصل أو تُعيّن القيمة الافتراضية للخاصية ShowSeriesName للتسميات الجديدة
            في مجموعة DataLabelCollection.
            عيّن هذه الخاصية بالقيمة سيؤدي أيضاً إلى تعيين هذه القيمة لخاصية ShowSeriesName 
            لجميع تسميات البيانات في مجموعة DataLabelCollection
            (مثلاً "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause to 
            جميع DataLabels[i].ShowSeriesName تكون مساوية للقيمة val).

### التعريف:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### انظر أيضًا
* فئة [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)