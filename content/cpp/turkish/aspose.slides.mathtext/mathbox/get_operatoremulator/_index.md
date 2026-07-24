---
title: get_OperatorEmulator()
second_title: Aspose.Slides için C++ API Referansı
description: "Operator Emulator. True olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini miras alır. Bu, örneğin, karakterin bir satır sonu noktası olarak kullanılabileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operator Emulator'lar genellikle bir veya daha fazla glifin '==' gibi bir operatör oluşturmak için birleştirildiği durumlarda kullanılır. Varsayılan değer: false"
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() metod

Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Varsayılan değer: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Açıklamalar

Örnek: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Ayrıca Bakınız

* Sınıf [MathBox](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)