---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by özelliği
İkinci pasta ya da çubukta hangi veri noktalarının yer alacağını belirlemenin yolunu tanımlar
            pie-of-pie veya bar-of-pie grafiklerinde.
            Bu özellik sadece bu serinin değil, aynı zamanda üst seriler grubunun tüm serilerinin
            özelliğidir - bu, uygun grup özelliğinin bir yansıtmasıdır. Bu yüzden bu özellik
            yalnızca okunabilir.
            Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın.
            Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okuma/yazma özelliğini kullanın.
            Salt okunur [`PieSplitType`](/slides/python-net/tr/aspose.slides.charts/piesplittype).


### Açıklamalar

1) Bu, ParentSeriesGroup.PieSplitBy özelliğinin bir yansıtmasıdır.
            2) Özellik değeri PieSplitType.Custom ise, ParentSeriesGroup.PieSplitCustomPoints özelliği ile özel bölme bilgisi tanımlayabilirsiniz.

### Tanım:
```python
@property
def pie_split_by(self):
    ...
```


### Ayrıca Bakınız
* sınıf [`IChartSeries`](/slides/python-net/tr/aspose.slides.charts/ichartseries)
* enum [`PieSplitType`](/slides/python-net/tr/aspose.slides.charts/piesplittype)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)