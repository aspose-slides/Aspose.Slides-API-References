---
title: Enclose()
second_title: Référence API Aspose.Slides pour C++
description: Encadre un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d’autres caractères comme cadre
type: docs
weight: 170
url: /fr/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) méthode

Encadre un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d’autres caractères comme cadre

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractère de début (généralement une parenthèse gauche) |
| endingCharacter | char16_t | Caractère de fin (généralement une parenthèse droite) |

### Valeur de retour

Si *beginningCharacter* et *endingCharacter* sont null, seules les propriétés correspondantes reçoivent des valeurs et aucun nouvel objet n’est créé (renvoie cette instance). Sinon, renvoie un nouvel élément mathématique de type Delimiter qui inclut les caractères spécifiés comme cadre et cette instance de [MathDelimiter](../) encadrée à l’intérieur.

## Remarques



Exemple :
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)