---
title: InsertClone()
second_title: Aspose.Slides C++ API hivatkozás
description: Beszúr egy példányt a megadott diából a gyűjtemény megadott pozíciójába.
type: docs
weight: 66
url: /hu/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) módszer


Beszúr egy példányt a megadott diából a gyűjtemény megadott pozíciójába.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozandó. |

### Visszatérő érték

Beszúrt dia.

## Megjegyzések

Diák klónozása különböző bemutatók között a dia mesterét is klónozhatja. Belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több példányának létrehozását. A mesterdiák kézi klónozása sem tiltott, sem regisztrált. Ha nagyobb irányítást szeretne a klónozási folyamat felett, használja a [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) vagy a [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) a diák klónozásához, valamint a [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) a mesterdiák klónozásához. 


Az alábbi példa azt mutatja, hogyan lehet egy másik pozícióba klónozni a [Presentation](../../presentation/)-ben. 
```cpp
// Példányosítsa a Presentation osztályt, amely egy bemutató fájlt képvisel
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Klónozza a kívánt diát a diák gyűjteményének végére ugyanabban a bemutatóban
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Klónozza a kívánt diát a megadott indexre ugyanabban a bemutatóban
slides->InsertClone(2, slides->idx_get(1));
// Mentse a módosított bemutatót a lemezre
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
Az alábbi példa azt mutatja, hogyan lehet egy másik pozícióba klónozni a [Presentation](../../presentation/)-ben. 
```cpp
// Példányosítsa a Presentation osztályt a forrás bemutató fájl betöltéséhez
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Példányosítsa a Presentation osztályt a cél PPTX-hez (ahová a dia klónozandó)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Mentse a cél bemutatót a lemezre
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) módszer


Beszúr egy példányt a megadott diából a gyűjtemény megadott pozíciójába.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozandó. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Elrendezés dia egy új diához. |

### Visszatérő érték

Beszúrt dia.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) módszer


Beszúr egy példányt a megadott forrásdiáról a gyűjtemény megadott pozíciójába. A megfelelő elrendezés automatikusan ki lesz választva a megadott mesterből (a megfelelő elrendezés az a elrendezés, amelynek típusa vagy neve megegyezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozandó. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Mester dia egy új diához. |
| allowCloneMissingLayout | **bool** | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis). |

### Visszatérő érték

Beszúrt dia.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [SlideCollection](../)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [IMasterSlide](../../imasterslide/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)