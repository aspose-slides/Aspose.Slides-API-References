---
title: set_SpellCheck()
second_title: Aspose.Slides C++ API referenciája
description: Beállít egy értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság hamisra van állítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha igazra van állítva, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték false.
type: docs
weight: 612
url: /hu/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) metódus

Beállít egy értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság hamisra van állítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha igazra van állítva, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Megjegyzés

A következő példa bemutatja a SpellCheck jelző engedélyezését a bemutató mentése előtt:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Az első dián az első alakzat első szövegrészéhez való hozzáférés
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// A helyesírás-ellenőrzés engedélyezése ehhez a szövegrészhez
portion->get_PortionFormat()->set_SpellCheck(true);
// A módosított bemutató mentése
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [BasePortionFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)