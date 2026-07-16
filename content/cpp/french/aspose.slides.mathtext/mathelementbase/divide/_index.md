---
title: Divide()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une fraction avec ce numérateur et le dénominateur spécifié
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) méthode


Crée une fraction avec ce numérateur et le dénominateur spécifié

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dénominateur |

### Valeur de retour

nouvelle fraction
## Remarques



Exemple : 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) méthode


Crée une fraction avec ce numérateur et le dénominateur spécifié

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Dénominateur |

### Valeur de retour

nouvelle fraction
## Remarques



Exemple : 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) méthode


Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dénominateur |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Type de fraction : Bar, NoBar, Skewed, Linear |

### Valeur de retour

nouvelle fraction
## Remarques



Exemple : 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) méthode


Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Dénominateur |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Type de fraction : Bar, NoBar, Skewed, Linear |

### Valeur de retour

nouvelle fraction
## Remarques



Exemple : 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Voir aussi

* Enumération [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFraction](../../imathfraction/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)