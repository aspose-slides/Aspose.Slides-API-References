---
title: AddFallBackFonts()
second_title: Aspose.Slides C++ API referenciája
description: Új betűtípust (vagy betűtípusokat) ad a FallBack betűtípusok listájához.
type: docs
weight: 79
url: /hu/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) metódus

Új betűtípust (vagy betűtípusokat) ad a FallBack betűtípusok listájához.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | FallBack-hez használandó betűtípus neve vagy nevei (vesszővel elválasztva) |
## Megjegyzések

```cpp
// Új FontFallBackRule példány létrehozása
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Második betűtípust ad a szabályhoz
newRule->AddFallBackFonts(u"MS Gothic");
//Harmadik és negyedik betűtípusokat ad a szabályhoz
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metódus

Új betűtípusokat ad a FallBack betűtípusok listájához.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack-hez használandó betűtípus neve vagy nevei (vesszővel elválasztva) |
## Megjegyzések

```cpp
// Új FontFallBackRule példány létrehozása
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// További három betűtípust ad a szabályhoz
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [FontFallBackRule](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)