---
title: FontFamily()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří novou instanci třídy FontFamily, která představuje rodinu písma se zadaným názvem.
type: docs
weight: 1
url: /cs/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) konstruktor


Vytvoří novou instanci třídy [FontFamily](../), která představuje rodinu písma se zadaným názvem.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název rodiny písma |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) konstruktor


Vytvoří novou instanci [FontFamily](../) ve zadané FontCollection se zadaným názvem.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název rodiny písma |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | FontCollection, která obsahuje tuto instanci. |

## FontFamily::FontFamily(Text::GenericFontFamilies) konstruktor


Vytvoří novou instanci [FontFamily](../) ze specifikované obecné rodiny písma.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | Hodnota GenericFontFamilies pro vytvoření [FontFamily](../). |

## Viz také

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [FontFamily](../)
* Třída [FontCollection](../../../system.drawing.text/fontcollection/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)