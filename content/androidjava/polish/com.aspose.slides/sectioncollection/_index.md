---
title: SectionCollection
second_title: Aspose.Slides dla Androida – Referencja API Java
description: Reprezentuje kolekcję sekcji.
type: docs
url: /pl/com.aspose.slides/sectioncollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Reprezentuje kolekcję sekcji.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Dodaje sekcję slajdów rozpoczynającą się od określonego slajdu. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Dodaje pustą sekcję na koniec kolekcji. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Dodaje pustą sekcję w określonej pozycji kolekcji. |
| [size()](#size--) | Pobiera liczbę elementów faktycznie zawartych w kolekcji. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Zwraca indeks określonej sekcji w kolekcji. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Usuwa sekcję i slajdy zawarte w sekcji. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Usuwa sekcję. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Przenosi sekcję i jej slajdy z kolekcji do określonej pozycji. |
| [clear()](#clear--) | Usuwa wszystkie sekcje z kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje całą kolekcję do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Pobiera element pod określonym indeksem. Tylko do odczytu [ISection](../../com.aspose.slides/isection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Dodaje sekcję slajdów rozpoczynającą się od określonego slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Pierwszy slajd sekcji |

**Zwraca:**
[ISection](../../com.aspose.slides/isection) - Dodana sekcja.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Dodaje pustą sekcję na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |

**Zwraca:**
[ISection](../../com.aspose.slides/isection) - Dodana sekcja.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Dodaje pustą sekcję w określonej pozycji kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |
| index | int | Indeks nowej sekcji. |

**Zwraca:**
[ISection](../../com.aspose.slides/isection) - Dodana sekcja.
### size() {#size--}
```
public final int size()
```

Pobiera liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Zwraca indeks określonej sekcji w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do znalezienia. |

**Zwraca:**
int - Indeks sekcji lub -1, jeśli sekcja nie pochodzi z tej kolekcji.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Usuwa sekcję i slajdy zawarte w sekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do usunięcia z kolekcji. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Usuwa sekcję. Slajdy zawarte w sekcji zostaną połączone z poprzednią sekcją.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do usunięcia z kolekcji. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Przenosi sekcję i jej slajdy z kolekcji do określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do przeniesienia. |
| index | int | Docelowy indeks. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie sekcje z kolekcji.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje całą kolekcję do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa |
| index | int | Indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - An java.util.Iterator for the entire collection.