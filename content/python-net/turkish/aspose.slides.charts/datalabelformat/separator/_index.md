---
title: separator property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## separator özelliği
Bir Variant temsil eden, bir grafikteki veri etiketleri için kullanılan separator'ı ayarlar veya döndürür.
            Okunur/yazılır **str**.

### Açıklamalar

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise bu özellik, DataLabelCollection koleksiyonundaki yeni veri etiketleri için Separator özelliğinin varsayılan değerini alır veya belirler. Bu özelliği bir değerle ayarlamak, aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketlerinin Separator özelliğine de ayarlar (ör. "DataLabels.DefaultDataLabelFormat.Separator = val;" tüm DataLabels[i].Separator değerinin val olduğuna neden olur).

### Tanım:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)