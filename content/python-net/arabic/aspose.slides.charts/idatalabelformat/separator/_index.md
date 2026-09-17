---
title: separator property
second_title: Aspose.Slides للـ Python عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## خاصية الفاصل
يضبط أو يُرجِع Variant يمثل الفاصل المستخدم لتسميات البيانات على مخطط.
            قراءة/كتابة **str**.


### ملاحظات
إذا كان عنصر الأب لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه
            الخاصية تحصل أو تضبط القيمة الافتراضية للخاصية Separator للبيانات الجديدة
            في مجموعة DataLabelCollection.
            ضبط هذه الخاصية بالقيمة يؤدي أيضاً إلى ضبط هذه القيمة للخاصية Separator
            لجميع تسميات البيانات في مجموعة DataLabelCollection
            (مثال: "DataLabels.DefaultDataLabelFormat.Separator = val;" يتسبب في
            أن جميع DataLabels[i].Separator يساوي val).

### التعريف:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### انظر أيضا
* الفئة [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)