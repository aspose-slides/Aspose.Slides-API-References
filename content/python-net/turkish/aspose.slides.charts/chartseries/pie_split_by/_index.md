---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by özelliği
Bir pasta-pasta veya çubuk-pasta grafikinde ikinci pasta veya çubukta hangi veri noktalarının yer alacağını belirlemenin yolunu belirtir.  
Bu özellik yalnızca bu seriye değil, aynı zamanda ana seriler grubunun tüm serilerine aittir - bu, ilgili grup özelliğinin bir yansıtmasıdır. Bu nedenle bu özellik salt okunurdur.  
Ana seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın.  
Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okuma/yazma özelliğini kullanın.  
Salt okunur [`PieSplitType`](/slides/python-net/tr/aspose.slides.charts/piesplittype).

### Açıklamalar

1) Bu, ParentSeriesGroup.PieSplitBy özelliğinin bir yansıtmasıdır.  
2) Eğer özellik değeri PieSplitType.Custom ise, ParentSeriesGroup.PieSplitCustomPoints özelliği ile özel bölme bilgisi tanımlayabilirsiniz.

### Tanım:
```python
@property
def pie_split_by(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`ChartSeries`](/slides/python-net/tr/aspose.slides.charts/chartseries)
* enum [`PieSplitType`](/slides/python-net/tr/aspose.slides.charts/piesplittype)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)