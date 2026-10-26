---
title: ToBox()
second_title: Aspose.Slides for C++ API Referansı
description: Bu öğeyi, bir denklem ya da başka bir matematiksel metin örneğinin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne, örneğin, hizalama noktasına sahip ya da sahip olmayan bir operatör öykünücüsü, bir satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin verilmeyecek şekilde gruplanabilir.
type: docs
weight: 274
url: /tr/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() metodu


Bu öğeyi, bir denklem ya da başka bir matematiksel metin örneğinin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne (örneğin) hizalama noktasıyla ya da hizalama noktası olmadan bir operatör öykünücüsü olarak, bir satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin verilmeyecek şekilde gruplanabilir.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```


### Dönüş Değeri

Bu öğe yerleştirilmiş mantıksal kutu
## Açıklamalar



Örnek: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBox](../../imathbox/)
* Sınıf [IMathElement](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)