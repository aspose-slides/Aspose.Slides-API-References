---
title: Join()
second_title: Référence API Aspose.Slides pour C++
description: Joint un élément mathématique et forme un bloc mathématique
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) method


Joint un élément mathématique et forme un bloc mathématique

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | L'élément à joindre |

### Valeur de retour

Un nouveau [IMathBlock](../../imathblock/) contenant cette instance et l'argument spécifié
## Remarques



Exemple :
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) method


Joint un texte mathématique et forme un bloc mathématique

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Texte mathématique à joindre |

### Valeur de retour

Un nouveau [IMathBlock](../../imathblock/) contenant cette instance et l'argument spécifié
## Remarques



Exemple :
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)