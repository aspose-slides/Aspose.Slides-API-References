---
title: MathBar()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa MathBar com barra superior (Posição superior)
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) construtor


Inicializa [MathBar](../) com barra superior (Posição superior)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento base ao qual a barra é aplicada |
## Observações



Exemplo: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) construtor


Inicializa [MathBar](../) com a posição especificada

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento base ao qual a barra é aplicada |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posição da linha da barra. |
## Observações



Exemplo: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## Ver Também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)