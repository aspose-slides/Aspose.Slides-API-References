---
title: ToBorderBox()
second_title: Référence API Aspose.Slides for C++
description: Place cet élément dans une border-box
type: docs
weight: 261
url: /fr/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() method


Place cet élément dans une border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Return Value

Border-box avec cet élément placé à l'intérieur
## Remarks



Exemple: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) method


Place cet élément dans une border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | Masquer le bord supérieur |
| hideBottom | **bool** | Masquer le bord inférieur |
| hideLeft | **bool** | Masquer le bord gauche |
| hideRight | **bool** | Masquer le bord droit |
| strikethroughHorizontal | **bool** | Barré horizontal de la border-box |
| strikethroughVertical | **bool** | Barré vertical de la border-box |
| strikethroughBottomLeftToTopRight | **bool** | Barré de la border-box du coin inférieur gauche au coin supérieur droit |
| strikethroughTopLeftToBottomRight | **bool** | Barré de la border-box du coin supérieur gauche au coin inférieur droit |

### Return Value

Border-box avec cet élément placé à l'intérieur
## Remarks



Exemple: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)