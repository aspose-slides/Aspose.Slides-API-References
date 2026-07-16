---
title: MathBorderBox()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un élément MathBorderBox avec une bordure rectangulaire
type: docs
weight: 222
url: /fr/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) constructor

Crée [MathBorderBox](../) élément avec une bordure rectangulaire

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément de base auquel la boîte de bordure est appliquée. Peut être nul. |
## Remarques



Exemple:
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) constructor

Crée [MathBorderBox](../) élément

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément de base auquel la boîte de bordure est appliquée |
| hideTop | **bool** | Masquer le bord supérieur |
| hideBottom | **bool** | Masquer le bord inférieur |
| hideLeft | **bool** | Masquer le bord gauche |
| hideRight | **bool** | Masquer le bord droit |
| strikethroughHorizontal | **bool** | Barrer horizontal |
| strikethroughVertical | **bool** | Barrer vertical |
| strikethroughBottomLeftToTopRight | **bool** | Barrer du bas-gauche vers le haut-droit |
| strikethroughTopLeftToBottomRight | **bool** | Barrer du haut-gauche vers le bas-droit |
## Remarques



Exemple:
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBorderBox](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)