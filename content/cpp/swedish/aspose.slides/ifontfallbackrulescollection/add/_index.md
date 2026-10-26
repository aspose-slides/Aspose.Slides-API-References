---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny FallBack-regel i slutet av samlingen.
type: docs
weight: 14
url: /sv/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metod

Lägg till en ny FallBack-regel i slutet av samlingen.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Angiven regel för att lägga till |
## Anmärkningar



```cpp
auto pres = MakeObject<Presentation>();
//Hämtar en tom eller förinitialiserad regelsamling från FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Lägger till ny regel i samlingen
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IFontFallBackRule](../../ifontfallbackrule/)
* Klass [IFontFallBackRulesCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)