---
title: SetSuperscript()
second_title: Référence de l'API Aspose.Slides for C++
description: Crée un exposant
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) méthode

Crée un exposant

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (upper index on the right) |

### Valeur de retour

Nouvel élément mathématique de type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarques

Exemple :
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) méthode

Crée un exposant

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the right) |

### Valeur de retour

Nouvel élément mathématique de type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarques

Exemple :
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)