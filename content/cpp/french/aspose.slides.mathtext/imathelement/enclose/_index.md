---
title: Enclose()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Enveloppe un élément mathématique entre parenthèses
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() méthode

Enveloppe un élément mathématique entre parenthèses

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### Valeur de retour

L'élément mathématique de type [IMathDelimiter](../../imathdelimiter/) qui inclut les parenthèses

## Remarques

Exemple :
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) méthode

Enveloppe cet élément dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractère de début (généralement le crochet ouvrant) |
| endingCharacter | char16_t | Caractère de fin (généralement le crochet fermant) |

### Valeur de retour

L'élément mathématique de type [IMathDelimiter](../../imathdelimiter/) qui inclut les caractères spécifiés comme encadrement

## Remarques

Exemple :
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [IMathElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)