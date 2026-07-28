---
title: AddFallBackFonts()
second_title: Aspose.Slides C++ API referenciája
description: Új betűtípust ad a FallBack betűtípusok listájához.
type: docs
weight: 40
url: /hu/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) metódus

Új betűtípust ad a FallBack betűtípusok listájához.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Font neve vagy nevei (vesszővel elválasztva) a FallBack számára |

## Megjegyzések

```cpp
//Új példány létrehozása a FantFallBackRule-ból
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Második betűtípus hozzáadása a szabályhoz
newRule->AddFallBackFonts(u"MS Gothic");
//Harmadik és negyedik betűtípusok hozzáadása a szabályhoz
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metódus

Új betűtípusokat ad a FallBack betűtípusok listájához.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Font neve vagy nevei (vesszővel elválasztva) a FallBack számára |

## Megjegyzések

```cpp
//Új példány létrehozása a FontFallBackRule-hoz
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Három további betűtípus hozzáadása a szabályhoz
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [IFontFallBackRule](../)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)