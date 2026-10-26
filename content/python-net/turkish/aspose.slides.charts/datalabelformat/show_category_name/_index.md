---
title: show_category_name property
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name özelliği
Belirtilen bir grafiğin veri etiketi kategori adı görüntüleme davranışını temsil eder.
            True grafikteki veri etiketleri için kategori adını göstermek. False gizlemek.
            Okunur/yazılır **bool**.


### Açıklamalar

Eğer bu DataLabelFormat nesnesinin üst öğesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özelliği yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowCategoryName özelliğinin varsayılan değerini alır veya ayarlar.
            Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowCategoryName özelliğine de ayarlar.
            (örn. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" tüm DataLabels[i].ShowCategoryName değerinin val olmasına neden olur.)

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
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)