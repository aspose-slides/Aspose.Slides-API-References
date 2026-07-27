---
title: MathDelimiter()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa MathDelimiter com o elemento especificado como argumento base único
type: docs
weight: 144
url: /pt/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) construtor

Inicializa [MathDelimiter](../) com o elemento especificado como argumento base único

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento base ao qual o delimitador é aplicado. Pode ser nulo. |
## Observações



Exemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)