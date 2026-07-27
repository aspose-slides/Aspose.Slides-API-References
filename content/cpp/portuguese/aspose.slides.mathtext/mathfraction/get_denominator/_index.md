---
title: get_Denominator()
second_title: Referência da API Aspose.Slides para C++
description: Denominador
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() método


Denominador

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
```

## Observações


Exemplo: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathElement](../../imathelement/)
* classe [MathFraction](../)
* namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)