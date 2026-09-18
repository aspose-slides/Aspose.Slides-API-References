---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell özelliği
Belirtilen bir grafiğin veri etiketi hücre değeri gösterim davranışını temsil eder. 
True hücre değerini gösterir. False gizlemek için.
Okunur/Yazılabilir **bool**.

### Açıklama
Bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonuyse, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelValueFromCell özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowLabelValueFromCell özelliğine de ayarlar (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" tüm DataLabels[i].ShowLabelValueFromCell değerinin val olmasına neden olur).

### Tanım:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)