---
title: Enclose()
second_title: Référence API Aspose.Slides pour C++
description: Encadre un élément mathématique entre parenthèses
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() méthode

Encadre un élément mathématique entre parenthèses

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```

### Valeur de retour

L'élément mathématique de type [IMathDelimiter](../../imathdelimiter/) qui inclut les parenthèses
## Remarques



Exemple:
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) méthode

Encadre un élément mathématique avec les caractères spécifiés, tels que les parenthèses ou d'autres caractères comme cadre

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractère de début (généralement le crochet gauche) |
| endingCharacter | char16_t | Caractère de fin (généralement le crochet droit) |

### Valeur de retour

L'élément mathématique de type [IMathDelimiter](../../imathdelimiter/) qui inclut les caractères spécifiés comme cadre
## Remarques



Exemple:
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathElementBase](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)