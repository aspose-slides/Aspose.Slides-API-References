---
title: ToBorderBox()
second_title: Aspose.Slides pro C++ API Reference
description: Umístí tento prvek do border-boxu
type: docs
weight: 248
url: /cs/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() metoda


Umístí tento prvek do border-boxu

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Návratová hodnota

Border-box s tímto prvkem umístěným uvnitř
## Poznámky



Příklad: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metoda


Umístí tento prvek do border-boxu

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hideTop | **bool** | Skrýt horní okraj |
| hideBottom | **bool** | Skrýt spodní okraj |
| hideLeft | **bool** | Skrýt levý okraj |
| hideRight | **bool** | Skrýt pravý okraj |
| strikethroughHorizontal | **bool** | Horizontální přeškrtnutí Border Box |
| strikethroughVertical | **bool** | Vertikální přeškrtnutí Border Box |
| strikethroughBottomLeftToTopRight | **bool** | Přeškrtnutí Border Boxu od spodního levého k hornímu pravému |
| strikethroughTopLeftToBottomRight | **bool** | Přeškrtnutí Border Boxu od horního levého k dolnímu pravému |

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
* Třída [MathElementBase](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)