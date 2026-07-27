---
title: MathGroupingCharacter()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe MathGroupingCharacter com o caractere de agrupamento padrão U+23DF (CHAVE CURVADA INFERIOR)
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) construtor


Inicializa uma nova instância da classe [MathGroupingCharacter](../) com o caractere de agrupamento padrão U+23DF (CHAVE CURVADA INFERIOR)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento base ao qual a barra é aplicada |
## Observações



Exemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) construtor


Inicializa uma nova instância da classe [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento base ao qual a barra é aplicada |
| character | char16_t | Caractere de Agrupamento |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posição do caractere de agrupamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justificação vertical do caractere de agrupamento |
## Observações



Exemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Ver também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)