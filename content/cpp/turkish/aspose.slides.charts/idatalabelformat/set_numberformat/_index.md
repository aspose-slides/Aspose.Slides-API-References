---
title: set_NumberFormat()
second_title: Aspose.Slides için C++ API Referansı
description: "DataLabels nesnesi için format dizesini temsil eder. System::String yazın."
type: docs
weight: 40
url: /tr/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) metot


DataLabels nesnesi için format dizesini temsil eder. [System::String](../../../system/string/) yazın.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Açıklamalar



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```


Bu [DataLabelFormat](../../datalabelformat/) nesnesinin ebeveyni bir [DataLabelCollection](../../datalabelcollection/) veri etiketi koleksiyonu ise, bu özellik [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki yeni veri etiketleri için NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, o değer [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki tüm veri etiketleri için NumberFormat özelliğine de atanır (ör. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" tüm DataLabels[i].NumberFormat değerinin val olmasına neden olur). 
## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IDataLabelFormat](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)