---
title: ToBorderBox()
second_title: Référence API Aspose.Slides pour C++
description: Place cet élément dans une boîte de bordure
type: docs
weight: 248
url: /fr/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() méthode


Place cet élément dans une boîte de bordure

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Valeur de retour

Boîte de bordure avec cet élément placé à l'intérieur
## Remarques



Exemple :
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) méthode


Place cet élément dans une boîte de bordure

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | Masquer le bord supérieur |
| hideBottom | **bool** | Masquer le bord inférieur |
| hideLeft | **bool** | Masquer le bord gauche |
| hideRight | **bool** | Masquer le bord droit |
| strikethroughHorizontal | **bool** | Barré horizontal de la boîte de bordure |
| strikethroughVertical | **bool** | Barré vertical de la boîte de bordure |
| strikethroughBottomLeftToTopRight | **bool** | Barré de la boîte de bordure du bas-gauche au haut-droit |
| strikethroughTopLeftToBottomRight | **bool** | Barré de la boîte de bordure du haut-gauche au bas-droit |

### Valeur de retour

Boîte de bordure avec cet élément placé à l'intérieur
## Remarques



Exemple :
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)