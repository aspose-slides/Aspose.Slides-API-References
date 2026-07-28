---
title: set_SpellCheck()
second_title: Aspose.Slides C++ API referenciája
description: Beállít egy értéket, amely azt jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság false értékre van állítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true értékre van állítva, a helyesírás-ellenőrzés megengedett. Az alapértelmezett érték false.
type: docs
weight: 612
url: /hu/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) metódus

Beállít egy értéket, amely azt jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Amikor ez a tulajdonság false értékre van állítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true értékre van állítva, a helyesírás-ellenőrzés megengedett. Az alapértelmezett érték **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```
## Megjegyzések

A következő példa bemutatja a SpellCheck jelző engedélyezését a prezentáció mentése előtt: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Az első dián az első alakzaton belül az első szövegrész elérése
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// A helyesírás-ellenőrzés engedélyezése ehhez a szövegrészhez
portion->get_PortionFormat()->set_SpellCheck(true);
// A módosított prezentáció mentése
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```
## Lásd még

* Osztály [IBasePortionFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)