---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API Referansı
description: "Operatör Öykünücüsü. true olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin satır sonu için bir nokta görevi görebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Öykünücüleri, bir veya daha fazla glifin '==' gibi bir operatör oluşturmak için birleştirildiği durumlarda sıklıkla kullanılır. Varsayılan değer: false"
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) metot


Operatör Öykünücüsü. true olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin satır sonu için bir nokta olarak kullanılabileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Öykünücüleri genellikle bir veya daha fazla glifin '==' gibi bir operatör oluşturmak için birleştirildiği durumlarda kullanılır. Varsayılan değer: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Ayrıca Bakınız

* Sınıf [IMathBox](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)