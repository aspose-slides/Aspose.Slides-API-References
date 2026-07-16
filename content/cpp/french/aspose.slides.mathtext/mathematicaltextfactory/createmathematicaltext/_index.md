---
title: CreateMathematicalText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Créer un élément de texte mathématique vide
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() méthode

Créer un élément de texte mathématique vide

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### Valeur de retour

nouveau Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) méthode

Créer un élément de texte mathématique avec la valeur spécifiée

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | symbole unique à utiliser comme valeur de texte |

### Valeur de retour

nouveau Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) méthode

Créer un élément de texte mathématique vide avec la valeur spécifiée

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valeur de texte |

### Valeur de retour

nouveau Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) méthode

Créer un élément de texte mathématique vide avec la valeur spécifiée et les propriétés de mise en forme

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valeur de texte |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | paramètres de format de texte |

### Valeur de retour

nouveau Mathematical Text

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathematicalText](../../imathematicaltext/)
* Classe [MathematicalTextFactory](../)
* Classe [String](../../../system/string/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)