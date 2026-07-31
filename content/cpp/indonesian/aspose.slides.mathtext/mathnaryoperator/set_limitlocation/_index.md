---
title: set_LimitLocation()
second_title: Referensi API Aspose.Slides untuk C++
description: Lokasi batas (subskrip dan superskrip)
type: docs
weight: 79
url: /id/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) metode


Lokasi batas (subskrip dan superskrip)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
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
* RuangNama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)