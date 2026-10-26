---
title: show_category_name property
second_title: مرجع API Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name خاصية
يمثل سلوك عرض اسم الفئة لتسمية البيانات في مخطط محدد.
True لعرض اسم الفئة لتسميات البيانات في المخطط. False لإخفائه.
قراءة/كتابة **bool**.

### ملاحظات
إذا كان العنصر الأب لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذه الخاصية تحصل على أو تضبط القيمة الافتراضية لخاصية ShowCategoryName للتسميات الجديدة في مجموعة DataLabelCollection. ضبط هذه الخاصية بالقيمة يضبط أيضًا هذه القيمة لخاصية ShowCategoryName لجميع تسميات البيانات في مجموعة DataLabelCollection (أي "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" يتسبب في أن يصبح جميع DataLabels[i].ShowCategoryName مساويًا لـ val).

### التعريف:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### انظر أيضًا
* فئة [`DataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/datalabelformat)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)