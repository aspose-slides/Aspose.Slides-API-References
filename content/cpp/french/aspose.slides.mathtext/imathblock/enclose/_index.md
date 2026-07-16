---
title: Enclose()
second_title: Référence de l'API Aspose.Slides pour C++
description: Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d’autres, en les encadrant et en les délimitant à l’aide d’un caractère séparateur
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) méthode


Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d’autres, en les entourant et en les séparant avec un caractère séparateur

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractère de début (généralement le crochet ouvrant) |
| endingCharacter | char16_t | Caractère de fin (généralement le crochet fermant) |
| separatorCharacter | char16_t | Caractère séparateur |

### Valeur de retour

L'élément mathématique de type [IMathDelimiter](../../imathdelimiter/) qui inclut les caractères spécifiés comme encadrement et délimiteur
## Remarques



Exemple : 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [IMathBlock](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)