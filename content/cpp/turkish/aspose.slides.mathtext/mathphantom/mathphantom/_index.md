---
title: MathPhantom()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen temel matematik öğesini kullanarak MathPhantom sınıfının yeni bir örneğini başlatır.
type: docs
weight: 144
url: /tr/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) constructor

Belirtilen temel matematik öğesini kullanarak [MathPhantom](../) sınıfının yeni bir örneğini başlatır.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Phantom tarafından görünürlüğü ve yerleşimi kontrol edilecek temel [IMathElement](../../imathelement/). Bu öğe görünür ya da gizli olabilecek içeriği tanımlar, ancak çevredeki matematiğin geometrik hizalanmasını etkileyen hâlde kalır. |

## Açıklamalar

Phantom öğesi, temel ifadesinin görsel alanını zorunlu olarak görüntülemeksizin ayırmak veya bastırmak için kullanılır. OMML öğesi **<m:phant>** ile eşleşir.

Örnek:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathPhantom](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)