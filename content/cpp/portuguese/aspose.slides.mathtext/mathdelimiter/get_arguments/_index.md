---
title: get_Arguments()
second_title: Aspose.Slides para a Referência da API C++
description: Um ou mais elementos matemáticos separados por caracteres delimitadores
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() método

Um ou mais elementos matemáticos separados por caracteres delimitadores

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Classe [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)