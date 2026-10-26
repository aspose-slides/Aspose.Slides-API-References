---
title: ISectionCollection
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje kolekcję sekcji.
type: docs
url: /pl/com.aspose.slides/isectioncollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Reprezentuje kolekcję sekcji.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Dodaj nową sekcję rozpoczynającą się od określonego slajdu. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Dodaj pustą sekcję do określonej pozycji w kolekcji. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Usuń sekcję i slajdy zawarte w sekcji. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Usuń sekcję. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Przenosi sekcję i jej slajdy z kolekcji do określonej pozycji. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Dodaj pustą sekcję na koniec kolekcji. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Zwraca indeks określonej sekcji w kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie sekcje z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Pobiera element pod określonym indeksem. Tylko do odczytu [ISection](../../com.aspose.slides/isection).

Parametry:
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

Zwraca:
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Dodaj nową sekcję rozpoczynającą się od określonego slajdu.

Parametry:
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Pierwszy slajd sekcji |

Zwraca:
[ISection](../../com.aspose.slides/isection) - Dodana sekcja.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Dodaj pustą sekcję do określonej pozycji w kolekcji.

Parametry:
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |
| index | int | Indeks nowej sekcji. |

Zwraca:
[ISection](../../com.aspose.slides/isection) - Dodana sekcja.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Usuń sekcję i slajdy zawarte w sekcji.

Parametry:
| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do usunięcia z kolekcji. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Usuń sekcję. Slajdy zawarte w sekcji zostaną połączone z poprzednią sekcją.

Parametry:
| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do usunięcia z kolekcji. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Przenosi sekcję i jej slajdy z kolekcji do określonej pozycji.

Parametry:
| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do przeniesienia. |
| index | int | Docelowy indeks. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Dodaj pustą sekcję na koniec kolekcji.

Parametry:
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |

Zwraca:
[ISection](../../com.aspose.slides/isection) - Dodana sekcja.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Zwraca indeks określonej sekcji w kolekcji.

Parametry:
| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do wyszukania. |

Zwraca:
int - Indeks sekcji lub -1, jeśli sekcja nie pochodzi z tej kolekcji.
### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie sekcje z kolekcji.