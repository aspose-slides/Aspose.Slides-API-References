---
title: show_label_as_data_callout property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout özelliği
Belirtilen grafiğin veri etiketi, veri çağrısı olarak mı yoksa veri etiketi olarak mı görüntüleneceğini belirler.

            Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu
            özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLabelAsDataCallout özelliğinin varsayılan değerini alır veya ayarlar.
            Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowLabelAsDataCallout özelliğine de atar
            (ör. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" tüm DataLabels[i].ShowLabelAsDataCallout değerinin val olmasına neden olur).

### Tanım:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### See Also
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)