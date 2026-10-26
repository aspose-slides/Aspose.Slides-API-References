---
title: Add()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει έναν καθορισμένο κανόνα FallBack στο τέλος της συλλογής.
type: docs
weight: 40
url: /el/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) μέθοδος


Προσθέτει έναν καθορισμένο κανόνα FallBack στο τέλος της συλλογής.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Specified rule for adding |
## Παρατηρήσεις



```cpp
auto pres = MakeObject<Presentation>();
//Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Προσθήκη νέου κανόνα στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontFallBackRule](../../ifontfallbackrule/)
* Κλάση [FontFallBackRulesCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)