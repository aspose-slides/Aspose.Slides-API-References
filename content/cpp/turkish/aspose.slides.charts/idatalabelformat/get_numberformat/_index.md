---
title: get_NumberFormat()
second_title: Aspose.Slides for C++ API Referansı
description: "DataLabels nesnesi için biçim dizesini temsil eder. System::String okuyun."
type: docs
weight: 27
url: /tr/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() metod


DataLabels nesnesi için biçim dizesini temsil eder. [System::String](../../../system/string/) değerini okuyun.

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Açıklamalar



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```




Eğer bu [DataLabelFormat](../../datalabelformat/) nesnesinin ebeveyni bir [DataLabelCollection](../../datalabelcollection/) veri etiketi koleksiyonu ise, bu özellik [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki yeni veri etiketleri için NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki tüm veri etiketleri için NumberFormat özelliğine de uygulanır (ör. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" tüm DataLabels[i].NumberFormat değerinin val olmasına neden olur). 
## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IDataLabelFormat](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)