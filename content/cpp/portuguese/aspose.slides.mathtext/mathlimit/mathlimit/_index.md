---
title: MathLimit()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe MathLimit.
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathlimit/mathlimit/
---
## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) construtor


Inicializa uma nova instância da classe [MathLimit](../).

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)
```

## Observações


Exemplo:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"), false);
```

## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) construtor


Inicializa uma nova instância da classe [MathLimit](../) com limite inferior

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)
```

## Observações


Exemplo:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)