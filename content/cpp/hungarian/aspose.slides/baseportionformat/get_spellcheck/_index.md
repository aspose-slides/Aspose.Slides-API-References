---
title: get_SpellCheck()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság hamisra van állítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha igazra van állítva, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték false.
type: docs
weight: 599
url: /hu/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() metódus

Visszaad egy értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság hamisra van állítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha igazra van állítva, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Megjegyzés

A következő példa bemutatja a SpellCheck jelző engedélyezését a bemutató mentése előtt:
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

* Osztály [BasePortionFormat](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)