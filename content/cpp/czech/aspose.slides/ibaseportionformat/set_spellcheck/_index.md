---
title: set_SpellCheck()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Nastaví hodnotu určující, zda je pravopisná kontrola povolena pro část textu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, pravopisná kontrola je povolena. Výchozí hodnota je false.
type: docs
weight: 612
url: /cs/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) metoda

Nastaví hodnotu určující, zda je pravopisná kontrola povolena pro část textu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, pravopisná kontrola je povolena. Výchozí hodnota je **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## Poznámky

Následující příklad ukazuje povolení příznaku SpellCheck před uložením prezentace:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Přístup k první části textu uvnitř prvního tvaru na první snímku
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Povolit pravopisnou kontrolu pro tuto část textu
portion->get_PortionFormat()->set_SpellCheck(true);
// Uložit upravenou prezentaci
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IBasePortionFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)