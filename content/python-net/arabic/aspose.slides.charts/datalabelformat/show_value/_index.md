---
title: show_value property
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## خاصية show_value
يمثل سلوك عرض قيمة النسبة المئوية لعلامة البيانات في مخطط محدد. 
            True تعرض قيمة النسبة المئوية. False لإخفائها.
            قراءة/كتابة **bool**.


### ملاحظات

إذا كان الكائن DataLabelFormat هو مجموعة DataLabelCollection لعلامات البيانات إذن هذه
            خاصية تحصل على أو تضبط القيمة الافتراضية لخاصية ShowValue للبيانات الجديدة 
            علامات في مجموعة DataLabelCollection.
            تعيين هذه الخاصية بقيمة يضبط أيضاً هذه القيمة لخاصية ShowValue 
            لكل علامات البيانات في مجموعة DataLabelCollection
            (على سبيل المثال "DataLabels.DefaultDataLabelFormat.ShowValue = val;" يؤدي إلى 
            أن جميع DataLabels[i].ShowValue تساوي val).

### التعريف:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### انظر أيضًا
* فئة [`DataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/datalabelformat)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)