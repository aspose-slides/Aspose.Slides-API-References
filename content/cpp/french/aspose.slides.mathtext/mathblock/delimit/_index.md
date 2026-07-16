---
title: Delimit()
second_title: Référence API Aspose.Slides pour C++
description: Délimite les éléments enfants avec le caractère séparateur (sans les crochets)
type: docs
weight: 209
url: /fr/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) méthode

Délimite les éléments enfants avec le caractère séparateur (sans les crochets)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | Caractère séparateur |

### Valeur de retour

L'élément mathématique de type [IMathDelimiter](../../imathdelimiter/)

## Remarques



Exemple :
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathBlock](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)