---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines özelliği
Belirli bir grafiğin veri etiketi lider çizgileri görüntüleme davranışını temsil eder.  
True lider çizgileri gösterir. False gizlemek için.  
Okunabilir/Yazılabilir **bool**.

### Açıklamalar
Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki ShowLeaderLines özelliğinin varsayılan değerini alır veya ayarlar.  
Bu özelliği bir değerle ayarlamak aynı zamanda bu değeri DataLabelCollection koleksiyonundaki tüm veri etiketleri için ShowLeaderLines özelliğine de ayarlar.  
(ör. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" tüm DataLabels[i].ShowLeaderLines değerinin val olmasına neden olur).

### Tanım:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`DataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/datalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)