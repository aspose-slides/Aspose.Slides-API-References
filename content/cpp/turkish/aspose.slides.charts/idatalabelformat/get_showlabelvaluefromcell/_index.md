---
title: get_ShowLabelValueFromCell()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir grafiğin veri etiketi hücre değeri görüntüleme davranışını temsil eder. True hücre değerini gösterir. False gizler. Okunur bool.
type: docs
weight: 300
url: /tr/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() yöntemi

Belirtilen bir grafiğin veri etiketi hücre değeri görüntüleme davranışını temsil eder. True hücre değerini gösterir. False gizler. Okunur **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## Açıklamalar

Eğer bu [DataLabelFormat](../../datalabelformat/) nesnesinin ebeveyni bir [DataLabelCollection](../../datalabelcollection/) veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için [DataLabelCollection](../../datalabelcollection/) koleksiyonunda ShowLabelValueFromCell özelliğinin varsayılan değerini alır veya ayarlar. Bu özelliği bir değerle ayarlamak aynı zamanda bu değeri [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki tüm veri etiketleri için ShowLabelValueFromCell özelliğine de ayarlar (örnek: "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" tüm DataLabels[i].ShowLabelValueFromCell değerinin val olmasına neden olur).

## Ayrıca Bakınız

* Class [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)