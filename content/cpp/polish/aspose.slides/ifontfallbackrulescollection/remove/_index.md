---
title: Remove()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Usuwa pierwsze wystąpienie określonej reguły FallBack z kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) metoda

Usuwa pierwsze wystąpienie określonej reguły FallBack z kolekcji.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Reguła do usunięcia z kolekcji. |

## Uwagi

```cpp
auto pres = MakeObject<Presentation>();
//Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Dodawanie kilku reguł do kolekcji
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Pobieranie obiektu pierwszej reguły w kolekcji
auto firstRule = rulesList->idx_get(0);
//Usuwanie
rulesList->Remove(firstRule);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontFallBackRule](../../ifontfallbackrule/)
* Klasa [IFontFallBackRulesCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)