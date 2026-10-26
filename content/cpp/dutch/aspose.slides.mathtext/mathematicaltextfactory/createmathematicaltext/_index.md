---
title: CreateMathematicalText()
second_title: Aspose.Slides voor C++ API-referentie
description: Maak een leeg wiskundig tekstelement
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() methode


Maak een leeg wiskundig tekstelement

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```


### Retourwaarde

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) methode


Maak een wiskundig tekstelement met de opgegeven waarde

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathSymbol | char16_t | enkel symbool om als tekstwaarde te gebruiken |

### Retourwaarde

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) methode


Maak een leeg wiskundig tekstelement met de opgegeven waarde

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | tekstwaarde |

### Retourwaarde

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) methode


Maak een leeg wiskundig tekstelement met de opgegeven waarde en opmaak-eigenschappen

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | tekstwaarde |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | instellingen voor tekstopmaak |

### Retourwaarde

new Mathematical Text

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathematicalText](../../imathematicaltext/)
* Klasse [MathematicalTextFactory](../)
* Klasse [String](../../../system/string/)
* Klasse [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)