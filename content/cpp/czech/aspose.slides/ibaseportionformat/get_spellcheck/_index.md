---
title: get_SpellCheck()
second_title: Aspose.Slides pro C++ – reference API
description: Získá hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.
type: docs
weight: 599
url: /cs/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() metoda


Získá hodnotu, která určuje, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Poznámky


Následující příklad ukazuje, jak povolit příznak SpellCheck před uložením prezentace: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Přístup k prvnímu úseku textu uvnitř prvního tvaru na první snímku
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Povolit kontrolu pravopisu pro tento úsek textu
portion->get_PortionFormat()->set_SpellCheck(true);
// Uložit upravenou prezentaci
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IBasePortionFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)