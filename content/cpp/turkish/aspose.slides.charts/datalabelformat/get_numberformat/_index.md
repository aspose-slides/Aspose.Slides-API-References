---
title: get_NumberFormat()
second_title: Aspose.Slides for C++ API Referansı
description: "DataLabels nesnesi için biçim dizesini temsil eder. System::String okuyun."
type: docs
weight: 27
url: /tr/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() metot


DataLabels nesnesi için biçim dizesini temsil eder. Okuyun [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Açıklamalar



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```




Eğer bu [DataLabelFormat](../) nesnesinin üst öğesi bir [DataLabelCollection](../../datalabelcollection/) veri etiketi koleksiyonu ise, bu özellik [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki yeni veri etiketleri için NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki tüm veri etiketleri için NumberFormat özelliğine de uygulanır (örn. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" ifadesi tüm DataLabels[i].NumberFormat değerinin val olmasını sağlar). 


## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [DataLabelFormat](../)
* AdAlanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)