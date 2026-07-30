---
title: ToBorderBox()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Umístí tento prvek do border-boxu
type: docs
weight: 261
url: /cs/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() metoda

Umístí tento prvek do border-boxu

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Návratová hodnota

Border-box s tímto prvkem umístěným uvnitř
## Poznámky



Příklad: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metoda


Umístí tento prvek do border-boxu

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hideTop | **bool** | Skryt horní okraj |
| hideBottom | **bool** | Skryt spodní okraj |
| hideLeft | **bool** | Skryt levý okraj |
| hideRight | **bool** | Skryt pravý okraj |
| strikethroughHorizontal | **bool** | Vodorovné přeškrtnutí border-boxu |
| strikethroughVertical | **bool** | Svislé přeškrtnutí border-boxu |
| strikethroughBottomLeftToTopRight | **bool** | Přeškrtnutí od dolního levého ke hornímu pravému v border-boxu |
| strikethroughTopLeftToBottomRight | **bool** | Přeškrtnutí od horního levého ke spodnímu pravému v border-boxu |

### Návratová hodnota

Border-box s tímto prvkem umístěným uvnitř
## Poznámky



Příklad: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBorderBox](../../imathborderbox/)
* Třída [IMathElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)