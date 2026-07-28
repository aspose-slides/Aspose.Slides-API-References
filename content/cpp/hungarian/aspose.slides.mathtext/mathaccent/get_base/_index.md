---
title: get_Base()
second_title: Aspose.Slides C++ API referencia
description: Az argumentum, amelyre az akcentus alkalmazva lett
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() metódus


Az argumentum, amelyre az akcentus alkalmazva lett

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Megjegyzés


Példa: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathAccent](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)