---
title: InsertClone()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Wstawia kopię określonego slajdu master w wyznaczoną pozycję w kolekcji. Powiązane slajdy układu również zostaną skopiowane.
type: docs
weight: 105
url: /pl/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metoda

Wstawia kopię określonego slajdu master do określonej pozycji w kolekcji. Powiązane slajdy układu również zostaną skopiowane.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Wstawiony slajd master.

## Uwagi

Poniższy przykład pokazuje, jak sklonować slajd master w innym pliku PowerPoint [Presentation](../../presentation/).
```cpp
// Utwórz obiekt klasy Presentation, aby wczytać plik prezentacji źródłowej
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Utwórz obiekt klasy Presentation dla prezentacji docelowej (gdzie slajd ma być sklonowany)
auto destPres = System::MakeObject<Presentation>();

// Utwórz obiekt ISlide z kolekcji slajdów w prezentacji źródłowej wraz z
// Slajdem master
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Pobierz slajdy master z prezentacji docelowej
auto masters = destPres->get_Masters();
// Sklonuj wybrany slajd master z prezentacji źródłowej do kolekcji masterów w
// Prezentacji docelowej
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Kolekcja slajdów w prezentacji docelowej
auto slides = destPres->get_Slides();
// Sklonuj slajd źródłowy do kolekcji slajdów docelowych.
slides->AddClone(sourceSlide, iSlide, true);
// Zapisz prezentację docelową na dysku
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMasterSlide](../../imasterslide/)
* Klasa [MasterSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)