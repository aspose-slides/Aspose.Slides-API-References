---
title: Divide()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une fraction avec ce numérateur et le dénominateur spécifié
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) méthode

Crée une fraction avec ce numérateur et le dénominateur spécifié

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dénominateur |

### Valeur retournée

nouvelle fraction
## Remarques



Exemple : 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) méthode

Crée une fraction avec ce numérateur et le dénominateur spécifié

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Dénominateur |

### Valeur retournée

nouvelle fraction
## Remarques



Exemple : 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) méthode

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dénominateur |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Type de fraction : Bar, NoBar, Skewed, Linear |

### Valeur retournée

nouvelle fraction
## Remarques



Exemple : 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) méthode

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Dénominateur |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Type de fraction : Bar, NoBar, Skewed, Linear |

### Valeur retournée

nouvelle fraction
## Remarques



Exemple : 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Voir aussi

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFraction](../../imathfraction/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)