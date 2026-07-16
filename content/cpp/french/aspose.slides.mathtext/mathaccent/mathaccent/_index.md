---
title: MathAccent()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d'accent par défaut
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) constructeur


Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur de caractère d'accent par défaut

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | un élément mathématique auquel appliquer l'accent |
## Remarques



Exemple: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) constructeur


Crée un accent mathématique appliqué à un élément mathématique spécifié

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer l'accent |
| accentCharacter | char16_t | caractère d'accent |
## Remarques



Exemple: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathAccent](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)