---
title: Add()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Dodaj nową regułę FallBack na koniec kolekcji.
type: docs
weight: 14
url: /pl/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metoda

Dodaj nową regułę FallBack na koniec kolekcji.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Określona reguła do dodania |
## Uwagi

```cpp
auto pres = MakeObject<Presentation>();
//Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Dodawanie nowej reguły do kolekcji
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IFontFallBackRule](../../ifontfallbackrule/)
* Klasa [IFontFallBackRulesCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)