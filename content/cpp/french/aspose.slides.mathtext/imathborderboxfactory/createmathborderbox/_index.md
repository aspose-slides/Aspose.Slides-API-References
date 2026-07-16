---
title: CreateMathBorderBox()
second_title: Référence de l'API Aspose.Slides pour C++
description: Créer une boîte de bordure mathématique en l'appliquant à l'élément
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method


Créer une boîte de bordure mathématique en l'appliquant à l'élément

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer la boîte de bordure |

### Return Value

nouvel élément de boîte de bordure

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method


Créer une boîte de bordure mathématique en l'appliquant à l'élément

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | élément mathématique auquel appliquer la boîte de bordure |
| hideTop | **bool** | Masquer le bord supérieur |
| hideBottom | **bool** | Masquer le bord inférieur |
| hideLeft | **bool** | Masquer le bord gauche |
| hideRight | **bool** | Masquer le bord droit |
| strikethroughHorizontal | **bool** | Trait traversant horizontal de la boîte de bordure |
| strikethroughVertical | **bool** | Trait traversant vertical de la boîte de bordure |
| strikethroughBottomLeftToTopRight | **bool** | Trait traversant de la boîte de bordure du bas-gauche au haut-droit |
| strikethroughTopLeftToBottomRight | **bool** | Trait traversant de la boîte de bordure du haut-gauche au bas-droit |

### Return Value

nouvel élément de boîte de bordure

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBorderBoxFactory](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)