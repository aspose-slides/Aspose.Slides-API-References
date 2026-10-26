---
title: MathDelimiter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen öğeyi tek temel argüman olarak kullanarak MathDelimiter nesnesini başlatır
type: docs
weight: 144
url: /tr/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) yapıcı


Belirtilen öğeyi tek temel argüman olarak kullanarak [MathDelimiter](../)'yi başlatır

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ayırıcı uygulanan temel öğe. Null olabilir. |
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Ayrıca bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)