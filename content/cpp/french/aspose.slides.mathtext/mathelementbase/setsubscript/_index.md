---
title: SetSubscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un indice
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) méthode

Crée un indice

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Indice (indice inférieur à droite) |

### Valeur de retour

Nouvel élément mathématique du type [IMathSubscriptElement](../../imathsubscriptelement/)

## Remarques



Exemple :
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) méthode

Crée un indice

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Indice (indice inférieur à droite) |

### Valeur de retour

Nouvel élément mathématique du type [IMathSubscriptElement](../../imathsubscriptelement/)

## Remarques



Exemple :
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSubscriptElement](../../imathsubscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)