---
title: AddClone()
second_title: Aspose.Slides dla C++ – referencja API
description: Dodaje kopię określonego slajdu na koniec kolekcji.
type: docs
weight: 14
url: /pl/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) metoda


Dodaje kopię określonego slajdu na koniec kolekcji.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Nowy slajd.

## Uwagi



Podczas klonowania slajdu między różnymi prezentacjami, master slajdu może również zostać sklonowany. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego master slajdu. Ręczne klonowanie master slajdów nie będzie ani zapobiegane, ani rejestrowane. Jeśli potrzebujesz większej kontroli nad procesem klonowania, użyj [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) lub [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) do klonowania slajdów, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) lub [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) do klonowania układów oraz [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) do klonowania masterów. 
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metoda


Dodaje kopię określonego slajdu na koniec określonej sekcji.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) dla nowego slajdu. |

### Wartość zwracana

Nowy slajd.

## Uwagi



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Teraz druga sekcja zawiera kopię pierwszego slajdu.
```


## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metoda


Dodaje kopię określonego slajdu na koniec kolekcji.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Układ slajdu dla nowego slajdu. |

### Wartość zwracana

Nowy slajd.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metoda


Dodaje kopię określonego slajdu źródłowego na koniec kolekcji. Odpowiedni układ zostanie automatycznie wybrany z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (gdy allowCloneMissingLayout jest true) lub zostanie wyrzucony PptxEditException (gdy allowCloneMissingLayout jest false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slajd dla nowego slajdu. |
| allowCloneMissingLayout | **bool** | Jeśli nie ma odpowiedniego układu w określonym masterze, układ slajdu źródłowego zostanie sklonowany (gdy allowCloneMissingLayout jest true) lub zostanie wyrzucony PptxEditException (gdy allowCloneMissingLayout jest false). |

### Wartość zwracana

Nowy slajd.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlide](../../islide/)
* Klasa [ISlideCollection](../)
* Klasa [ISection](../../isection/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [IMasterSlide](../../imasterslide/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)