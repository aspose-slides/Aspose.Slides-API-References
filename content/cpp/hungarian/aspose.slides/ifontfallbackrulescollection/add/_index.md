---
title: Add()
second_title: Aspose.Slides C++ API hivatkozás
description: Új FallBack szabályt ad a gyűjtemény végéhez.
type: docs
weight: 14
url: /hu/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metódus


Új FallBack szabályt ad hozzá a gyűjtemény végéhez.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | A hozzáadáshoz megadott szabály |
## Megjegyzések



```cpp
auto pres = MakeObject<Presentation>();
//A FontsManager-ből üres vagy előre inicializált szabálygyűjtemény lekérése
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Új szabály hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontFallBackRule](../../ifontfallbackrule/)
* Osztály [IFontFallBackRulesCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)