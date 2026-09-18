---
title: separator property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator özelliği
Bir grafik üzerindeki veri etiketleri için kullanılan ayırıcıyı temsil eden Variant'ı ayarlar veya döndürür.
            Okunur/Yazılır **str**.


### Açıklamalar

Eğer bu DataLabelFormat nesnesinin ebeveyni bir DataLabelCollection veri etiketleri koleksiyonu ise, bu
            özellik DataLabelCollection koleksiyonundaki yeni veri 
            etiketleri için Separator özelliğinin varsayılan değerini alır veya ayarlar.
            Bu özelliği bir değerle ayarlamak aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin Separator özelliğine 
            ayarlar
            (ör. "DataLabels.DefaultDataLabelFormat.Separator = val;" tüm DataLabels[i].Separator değerinin val olmasına neden olur).

### Tanım:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### Diğer Bilgiler
* sınıf [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)