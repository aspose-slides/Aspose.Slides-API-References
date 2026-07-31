---
title: get_LimitLocation()
second_title: Referensi API Aspose.Slides untuk C++
description: Lokasi batas (subskrip dan superskrip)
type: docs
weight: 27
url: /id/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() metode


Lokasi batas (subskrip dan superskrip)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Keterangan


Contoh: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Lihat Juga

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Kelas [IMathNaryOperatorProperties](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)