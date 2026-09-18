---
title: show_category_name property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name özellik
Belirtilen bir grafiğin veri etiketi kategori adı gösterim davranışını temsil eder.
True bir grafikteki veri etiketleri için kategori adını görüntülemek için. False gizlemek için.
Okunur/yazılabilir **bool**.

### Açıklamalar
Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise bu
özellik, DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar.
Bu özelliği bir değerle ayarlamak aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowCategoryName özelliğine de ayarlar
(i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" tüm DataLabels[i].ShowCategoryName değerinin val olmasına neden olur).

### Tanım:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)