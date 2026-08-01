---
title: CreateMathematicalText()
second_title: Aspose.Slides voor C++ API-referentie
description: Maak een leeg wiskundig textelement
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() method

Maak een leeg wiskundig textelement

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Retourwaarde

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) method

Maak een wiskundig textelement met de opgegeven waarde

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathSymbol | char16_t | enkel symbool om te gebruiken als textelementwaarde |

### Retourwaarde

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) method

Maak een leeg wiskundig textelement met de opgegeven waarde

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textelementwaarde |

### Retourwaarde

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method

Maak een leeg wiskundig textelement met de opgegeven waarde en opmaak-eigenschappen

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | textelementwaarde |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | tekstopmaakinstellingen |

### Retourwaarde

new Mathematical Text

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathematicalText](../../imathematicaltext/)
* Class [IMathematicalTextFactory](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)