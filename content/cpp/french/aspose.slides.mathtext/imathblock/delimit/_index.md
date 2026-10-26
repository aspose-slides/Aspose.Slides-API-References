---
title: Delimit()
second_title: Référence API Aspose.Slides for C++
description: Délimite tous les éléments enfants avec le caractère séparateur (sans les crochets)
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) méthode

Délimite tous les éléments enfants avec le caractère séparateur (sans les crochets)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | Caractère utilisé comme séparateur |

### Valeur de retour

Instance de l'élément [IMathDelimiter](../../imathdelimiter/)

## Remarques



Exemple :
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)