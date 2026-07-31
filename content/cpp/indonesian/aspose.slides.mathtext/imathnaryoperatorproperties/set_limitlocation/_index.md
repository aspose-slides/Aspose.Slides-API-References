---
title: set_LimitLocation()
second_title: Referensi API Aspose.Slides untuk C++
description: Lokasi batas (subskrip dan superskrip)
type: docs
weight: 40
url: /id/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) metode

Lokasi batas (subskrip dan superskrip)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Catatan

Contoh:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Lihat Juga

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Kelas [IMathNaryOperatorProperties](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)