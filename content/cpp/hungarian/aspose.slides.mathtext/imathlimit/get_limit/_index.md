---
title: get_Limit()
second_title: Aspose.Slides C++ API Referencia
description: Limit argumentum
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() method

Limit argumentum

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Megjegyzés

Példa:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathLimit](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)