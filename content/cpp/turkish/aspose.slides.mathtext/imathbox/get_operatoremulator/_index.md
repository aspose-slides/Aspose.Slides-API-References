---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API Referansı
description: "Operatör Emülatörü. true olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlere hizalanabileceği anlamına gelir. Operatör Emülatörleri genellikle bir veya daha fazla glif bir operatör oluşturmak üzere birleştirildiğinde, örneğin '==' gibi, kullanılır. Varsayılan değer: false"
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() method


Operator Emulator. true olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini miras alır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlere hizalanabileceği anlamına gelir. Operator Emulators genellikle bir veya daha fazla glif bir operatör oluşturmak için birleştirildiğinde, örneğin '==' gibi, kullanılır. Varsayılan değer: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
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