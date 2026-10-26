---
title: ToBox()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öğeyi, bir denklemin bileşenlerini veya diğer matematiksel metin örneklerini gruplamak için kullanılan görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne (örneğin) hizalama noktasıyla veya hizalama noktası olmadan bir operatör öykünücüsü olarak, bir satır sonu noktası olarak kullanılabilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir.
type: docs
weight: 261
url: /tr/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() metot

Bu öğeyi, bir denklemin veya diğer matematiksel metin örneklerinin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne (örneğin) hizalama noktasıyla veya hizalama noktası olmadan bir operatör öykünücüsü olarak hizmet edebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```

### Dönüş Değeri

Bu öğenin içinde yer aldığı mantıksal kutu
## Açıklamalar

Örnek:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBox](../../imathbox/)
* Sınıf [MathElementBase](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)