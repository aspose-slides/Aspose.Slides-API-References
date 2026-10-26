---
title: Delimit()
second_title: Référence de l'API Aspose.Slides pour C++
description: Délimite les arguments en utilisant le caractère délimiteur spécifié
type: docs
weight: 144
url: /fr/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) méthode

Délimite les arguments en utilisant le caractère délimiteur spécifié

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | caractère délimiteur |

### Valeur de retour

Cet objet après l'application du caractère délimiteur

## Remarques



Exemple : 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)