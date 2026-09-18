---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name özelliği
Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. 
            True to show the series name. False to hide.
            Okuma/yazma **bool**.


### Açıklamalar

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketi koleksiyonu ise, bu
            özellik DataLabelCollection koleksiyonundaki yeni veri etiketleri için ShowSeriesName özelliğinin varsayılan değerini alır veya ayarlar.
            Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin ShowSeriesName özelliğine de ayarlar
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" tüm DataLabels[i].ShowSeriesName değerini val yapar).

### Tanım:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Ayrıca Bakınız
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)