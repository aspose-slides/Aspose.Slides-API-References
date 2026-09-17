---
title: show_label_value_from_cell property
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## خاصية show_label_value_from_cell
يمثل سلوك عرض قيمة خلية تسمية البيانات لمخطط محدد. 
            True يعرض قيمة الخلية. False لإخفائها.
            قراءة/كتابة **bool**.


### ملاحظات

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this خاصية gets or sets the default value of the ShowLabelValueFromCell خاصية for the new data 
            labels in the DataLabelCollection collection.
            Set this خاصية with value also sets this value to the ShowLabelValueFromCell خاصية 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" cause to 
            all DataLabels[i].ShowLabelValueFromCell is equal to val).

### التعريف:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### انظر أيضًا
* الفئة [`DataLabelFormat`](/slides/python-net/ar/aspose.slides.charts/datalabelformat)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)