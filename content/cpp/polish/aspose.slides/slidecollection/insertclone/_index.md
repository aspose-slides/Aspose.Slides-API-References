---
title: InsertClone()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wstawia kopię określonego slajdu na podaną pozycję w kolekcji.
type: docs
weight: 66
url: /pl/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metoda


Wstawia kopię określonego slajdu na podaną pozycję w kolekcji.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Wstawiony slajd.

## Uwagi



Podczas klonowania slajdu pomiędzy różnymi prezentacjami master slajdu może zostać również sklonowany. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego mastera slajdu. Ręczne klonowanie masterów slajdów nie będzie ani zapobiegane, ani rejestrowane. Jeśli potrzebujesz większej kontroli nad procesem klonowania, użyj [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) lub [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) do klonowania slajdów oraz [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) do klonowania masterów. 


Poniższy przykład pokazuje, jak sklonować w innym miejscu w obrębie [Presentation](../../presentation/). 
```cpp
// Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Sklonuj pożądany slajd na koniec kolekcji slajdów w tej samej prezentacji
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Sklonuj pożądany slajd do określonego indeksu w tej samej prezentacji
slides->InsertClone(2, slides->idx_get(1));
// Zapisz zmodyfikowaną prezentację na dysku
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 Poniższy przykład pokazuje, jak sklonować w innym miejscu w obrębie [Presentation](../../presentation/). 
```cpp
// Utwórz instancję klasy Presentation, aby wczytać plik prezentacji źródłowej
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Utwórz instancję klasy Presentation dla docelowego pliku PPTX (gdzie slajd ma być sklonowany)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Zapisz docelową prezentację na dysku
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metoda


Wstawia kopię określonego slajdu na podaną pozycję w kolekcji.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Slajd układu dla nowego slajdu. |

### Wartość zwracana

Wstawiony slajd.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metoda


Wstawia kopię określonego slajdu źródłowego na podaną pozycję w kolekcji. Odpowiedni układ zostanie wybrany automatycznie z określonego mastera (odpowiedni układ to układ o tym samym typie lub nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie wyrzucony wyjątek PptxEditException (jeśli allowCloneMissingLayout jest false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slajd główny dla nowego slajdu. |
| allowCloneMissingLayout | **bool** | Jeśli w określonym masterze nie ma odpowiedniego układu, wtedy układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie wyrzucony wyjątek PptxEditException (jeśli allowCloneMissingLayout jest false). |

### Wartość zwracana

Wstawiony slajd.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlide](../../islide/)
* Klasa [SlideCollection](../)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [IMasterSlide](../../imasterslide/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)