---
title: show_category_name property
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name خاصية
يمثل سلوك عرض اسم الفئة لتسمية البيانات في مخطط محدد.
True لعرض اسم الفئة لتسميات البيانات على المخطط. False لإخفائه.
قراءة/كتابة **bool**.


### ملاحظات

إذا كان العنصر الأب لهذا الكائن DataLabelFormat هو مجموعة DataLabelCollection من تسميات البيانات، فإن هذا
            الخاصية تحصل أو تعين القيمة الافتراضية للخاصية ShowCategoryName لتسميات البيانات الجديدة
            في مجموعة DataLabelCollection.
            تعيين هذه الخاصية بالقيمة يضبط أيضاً هذه القيمة للخاصية ShowCategoryName
            لجميع تسميات البيانات في مجموعة DataLabelCollection
            (على سبيل المثال "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" يؤدي إلى
            أن يكون جميع DataLabels[i].ShowCategoryName مساويًا لـ val).

### التعريف:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### راجع أيضاً
* فئة [`IDataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/idatalabelformat)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)