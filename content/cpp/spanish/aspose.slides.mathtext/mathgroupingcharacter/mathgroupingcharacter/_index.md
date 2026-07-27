---
title: MathGroupingCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase MathGroupingCharacter con el carácter de agrupación predeterminado U+23DF (BOTTOM CURLY BRACKET)
type: docs
weight: 92
url: /es/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) constructor

Inicializa una nueva instancia de la clase [MathGroupingCharacter](../) con el carácter de agrupación predeterminado U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El elemento base al que se aplica la barra |
## Comentarios

Ejemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) constructor

Inicializa una nueva instancia de la clase [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El elemento base al que se aplica la barra |
| character | char16_t | Carácter de agrupación |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posición del carácter de agrupación |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justificación vertical del carácter de agrupación |
## Comentarios

Ejemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Ver también

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)