---
title: MathBox()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa MathBox com o elemento especificado como argumento
type: docs
weight: 144
url: /pt/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) constructor

Inicializa [MathBox](../) com o elemento especificado como argumento

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento base ao qual a caixa é aplicada. Pode ser nulo. |
## Observações



Exemplo: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)