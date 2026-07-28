---
title: InsertClone()
second_title: Aspose.Slides for C++ API-referencia
description: Beszúr egy példányt a megadott mester diából a gyűjtemény megadott pozíciójába. A kapcsolt elrendezési diák is másolva lesz.
type: docs
weight: 105
url: /hu/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metódus

Beszúr egy példányt a megadott mester diából a gyűjtemény megadott pozíciójába. A kapcsolt elrendezési diák is másolva lesz.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) klónozáshoz. |

### Visszatérési érték

Beszúrt mester dia.

## Megjegyzés

Az alábbi példa bemutatja, hogyan lehet klónozni egy mester diát egy másik PowerPoint [Presentation](../../presentation/)-ben.
```cpp
// A Presentation osztály példányosítása a forrás prezentációs fájl betöltéséhez
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// A Presentation osztály példányosítása a cél prezentációhoz (ahová a dia másolva lesz)
auto destPres = System::MakeObject<Presentation>();

// ISlide példányosítása a forrás prezentáció diák gyűjteményéből együtt
// Mester dia
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// A cél prezentáció Mester diait lekéri
auto masters = destPres->get_Masters();
// A kívánt mester dia klónozása a forrás prezentációból a mesterek gyűjteményébe a
// Cél prezentáció
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Diák gyűjteménye a cél prezentációban
auto slides = destPres->get_Slides();
// Forrás dia klónozása a cél diák gyűjteményébe.
slides->AddClone(sourceSlide, iSlide, true);
// A cél prezentáció mentése lemezre
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMasterSlide](../../imasterslide/)
* Osztály [MasterSlideCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)