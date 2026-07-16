---
title: Enclose()
second_title: Référence de l'API Aspose.Slides pour C++
description: Encadre les éléments enfants de ce bloc avec les caractères spécifiés, tels que des parenthèses ou d'autres caractères, comme encadrement
type: docs
weight: 222
url: /fr/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) méthode


Encadre les éléments enfants de ce bloc avec les caractères spécifiés, tels que des parenthèses ou d’autres caractères, comme encadrement

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractère de début (généralement le crochet gauche) |
| endingCharacter | char16_t | Caractère de fin (généralement le crochet droit) |

### Valeur de retour

L'élément mathématique de type [IMathDelimiter](../../imathdelimiter/) qui inclut les caractères spécifiés comme encadrement
## Remarques



Exemple:
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) méthode


Encadre les éléments enfants de ce bloc avec les caractères spécifiés, tels que des parenthèses ou d’autres, comme encadrement et les délimite avec un caractère séparateur

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractère de début (généralement le crochet gauche) |
| endingCharacter | char16_t | Caractère de fin (généralement le crochet droit) |
| separatorCharacter | char16_t | Caractère séparateur |

### Valeur de retour

L'élément mathématique de type [IMathDelimiter](../../imathdelimiter/) qui inclut les caractères spécifiés comme encadrement et délimiteur
## Remarques



Exemple:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathBlock](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)