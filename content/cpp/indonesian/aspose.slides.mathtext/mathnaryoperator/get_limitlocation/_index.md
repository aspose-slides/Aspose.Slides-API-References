---
title: get_LimitLocation()
second_title: Referensi API Aspose.Slides untuk C++
description: Lokasi batas (subskrip dan superskrip)
type: docs
weight: 66
url: /id/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() metode


Lokasi batas (subskrip dan superskrip)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Catatan


Contoh: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Lihat Juga

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Kelas [MathNaryOperator](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)