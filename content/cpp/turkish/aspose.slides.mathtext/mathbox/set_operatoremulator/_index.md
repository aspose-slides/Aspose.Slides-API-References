---
title: set_OperatorEmulator()
second_title: Aspose.Slides için C++ API Referansı
description: "Operatör Emülatörü. true olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin bir satır sonu noktası olarak kullanılabileceği ve diğer operatörlere hizalanabileceği anlamına gelir. Operatör Emülatörleri, bir veya daha fazla glifin '==' gibi bir operatör oluşturmak için birleştirildiği durumlarda sıkça kullanılır. Varsayılan değer: false"
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) metod

Operatör Emülatörü. true olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin bir satır sonu noktası olarak kullanılabileceği ve diğer operatörlere hizalanabileceği anlamına gelir. Operatör Emülatörleri genellikle bir veya daha fazla glif bir operatör oluşturmak üzere birleştirildiğinde kullanılır, örneğin '==' gibi. Varsayılan değer: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Açıklamalar

Örnek: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Ayrıca Bakınız

* Sınıf [MathBox](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)