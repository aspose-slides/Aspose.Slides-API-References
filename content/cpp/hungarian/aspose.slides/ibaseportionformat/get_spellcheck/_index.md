---
title: get_SpellCheck()
second_title: Aspose.Slides for C++ API referencia
description: Visszaad egy értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság false értékre van állítva, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha true értékre van állítva, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték false.
type: docs
weight: 599
url: /hu/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() metódus


Értéket ad vissza, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság **false** értékre van állítva, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha **true** értékre van állítva, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték a **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Megjegyzések


A következő példa bemutatja a SpellCheck jelölő engedélyezését a bemutató mentése előtt:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IBasePortionFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)