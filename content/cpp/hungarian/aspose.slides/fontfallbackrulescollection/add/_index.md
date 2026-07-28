---
title: Add()
second_title: Aspose.Slides C++ API referencia
description: Hozzáad egy megadott FallBack szabályt a gyűjtemény végéhez.
type: docs
weight: 40
url: /hu/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metódus


Hozzáad egy megadott FallBack szabályt a gyűjtemény végéhez.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Megadott szabály a hozzáadáshoz |
## Megjegyzések


```cpp
auto pres = MakeObject<Presentation>();
//A FontsManagerből üres vagy előre inicializált szabálygyűjtemény lekérése
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Új szabály hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontFallBackRule](../../ifontfallbackrule/)
* Osztály [FontFallBackRulesCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)