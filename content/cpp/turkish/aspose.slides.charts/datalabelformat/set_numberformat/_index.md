---
title: set_NumberFormat()
second_title: Aspose.Slides için C++ API Referansı
description: "DataLabels nesnesi için biçim dizesini temsil eder. System::String yazın."
type: docs
weight: 40
url: /tr/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) method


DataLabels nesnesi için biçim dizesini temsil eder. [System::String](../../../system/string/) yazın.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Açıklamalar



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Eğer bu [DataLabelFormat](../) nesnesinin ebeveyni bir [DataLabelCollection](../../datalabelcollection/) veri etiketi koleksiyonu ise, bu özellik [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki yeni veri etiketleri için NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. Bu özellik bir değerle ayarlandığında, aynı değer [DataLabelCollection](../../datalabelcollection/) koleksiyonundaki tüm veri etiketlerinin NumberFormat özelliği için de ayarlanır (ör. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" tüm DataLabels[i].NumberFormat değerinin val olmasına neden olur).



## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [DataLabelFormat](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)