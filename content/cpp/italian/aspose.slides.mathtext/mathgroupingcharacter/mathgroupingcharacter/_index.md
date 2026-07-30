---
title: MathGroupingCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe MathGroupingCharacter con il carattere di raggruppamento predefinito U+23DF (BOTTOM CURLY BRACKET)
type: docs
weight: 92
url: /it/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) costruttore


Inizializza una nuova istanza della classe [MathGroupingCharacter](../) con il carattere di raggruppamento predefinito U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento di base al quale viene applicata la barra |
## Note



Esempio: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) costruttore


Inizializza una nuova istanza della classe [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento di base al quale viene applicata la barra |
| character | char16_t | Carattere di raggruppamento |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posizione del carattere di raggruppamento |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Giustificazione verticale del carattere di raggruppamento |
## Note



Esempio: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)