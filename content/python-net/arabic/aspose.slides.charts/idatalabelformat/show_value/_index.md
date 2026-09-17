---
title: show_value property
second_title: دليل مرجع Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## خاصية show_value
يمثل سلوك عرض قيمة النسبة المئوية لتسمية البيانات للمخطط المحدد. 
True يعرض قيمة النسبة المئوية. False لإخفائها.
قراءة/كتابة **bool**.

### ملاحظات

إذا كان الأصل لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه
الخاصية تحصل على أو تعيين القيمة الافتراضية لخاصية ShowValue للبيانات
الجديدة في مجموعة DataLabelCollection.
تعيين هذه الخاصية بالقيمة أيضًا يضع هذه القيمة لخاصية ShowValue
 لجميع تسميات البيانات في مجموعة DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" يؤدي إلى
 أن جميع DataLabels[i].ShowValue تكون مساوية للقيمة val).

### التعريف:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### راجع أيضًا
* الفئة [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)