---
title: set_SpellCheck()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Nastavuje hodnotu, která určuje, zda je pro textovou část povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je false.
type: docs
weight: 612
url: /cs/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) metoda


Nastavuje hodnotu, která určuje, zda je pro textovou část povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Poznámky


Následující příklad ukazuje povolení příznaku SpellCheck před uložením prezentace: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
portion->get_PortionFormat()->set_SpellCheck(true);
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [BasePortionFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)