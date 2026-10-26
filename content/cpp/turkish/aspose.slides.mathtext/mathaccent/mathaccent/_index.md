---
title: MathAccent()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bir matematik öğesine varsayılan aksan karakteri değeriyle bir matematik aksanı oluşturur
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) yapıcı


Belirtilen bir matematik öğesine varsayılan aksan karakteri değeriyle bir matematik aksanı oluşturur

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | aksan uygulanacak bir matematik öğesi |
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) yapıcı


Belirtilen bir matematik öğesine bir matematik aksanı oluşturur

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | aksan uygulanacak matematik öğesi |
| accentCharacter | char16_t | aksan karakteri |
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathAccent](../)
* İsimAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)