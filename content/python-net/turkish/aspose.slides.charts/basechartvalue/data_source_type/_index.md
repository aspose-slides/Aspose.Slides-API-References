---
title: data_source_type property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/basechartvalue/data_source_type/
weight: 20
---
## data_source_type özelliği
Veri kaynağının AsCell, AsCells, AsLiteralString ya da AsLiteralDouble 
            özelliğinin türevlerde geçerli olup olmadığını belirtir. Başka bir deyişle Data özelliğinin değer tipini belirtir.
            Okunabilir/Yazılabilir [`DataSourceType`](/slides/python-net/tr/aspose.slides.charts/datasourcetype).

### Açıklamalar
ChartDataPointCollection içerisindeki noktalar için bu özellik yalnızca okunabilir. 
            Bu durumda bu özelliğin değerini değiştirmek için 
            ChartDataPointCollection.DataSourceTypeFor<...> özelliklerinden birini kullanabilirsiniz.

### Tanım:
```python
@property
def data_source_type(self):
    ...

@data_source_type.setter
def data_source_type(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`BaseChartValue`](/slides/python-net/tr/aspose.slides.charts/basechartvalue)
* enum [`DataSourceType`](/slides/python-net/tr/aspose.slides.charts/datasourcetype)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)