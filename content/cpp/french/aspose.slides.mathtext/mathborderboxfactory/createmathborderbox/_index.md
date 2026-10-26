---
title: CreateMathBorderBox()
second_title: Référence de l'API Aspose.Slides pour C++
description: Créer une boîte de bordure mathématique en l'appliquant à l'élément
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) méthode

Créer une boîte de bordure mathématique en l'appliquant à l'élément

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer la boîte de bordure |

### Valeur de retour

nouvel élément de boîte de bordure

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) méthode

Créer une boîte de bordure mathématique en l'appliquant à l'élément

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer la boîte de bordure |
| hideTop | **bool** | Masquer le bord supérieur |
| hideBottom | **bool** | Masquer le bord inférieur |
| hideLeft | **bool** | Masquer le bord gauche |
| hideRight | **bool** | Masquer le bord droit |
| strikethroughHorizontal | **bool** | Barré horizontal de la boîte de bordure |
| strikethroughVertical | **bool** | Barré vertical de la boîte de bordure |
| strikethroughBottomLeftToTopRight | **bool** | Barré de la boîte de bordure du bas-gauche vers le haut-droit |
| strikethroughTopLeftToBottomRight | **bool** | Barré de la boîte de bordure du haut-gauche vers le bas-droit |

### Valeur de retour

nouvel élément de boîte de bordure

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBorderBoxFactory](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)