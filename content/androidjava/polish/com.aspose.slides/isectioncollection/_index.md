---
title: ISectionCollection
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje kolekcję sekcji.
type: docs
url: /pl/com.aspose.slides/isectioncollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Reprezentuje kolekcję sekcji.

## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Dodaje nową sekcję rozpoczynającą się od określonego slajdu. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Dodaje pustą sekcję na określonej pozycji w kolekcji. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Usuwa sekcję oraz slajdy znajdujące się w tej sekcji. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Usuwa sekcję. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Przenosi sekcję i jej slajdy z kolekcji na określoną pozycję. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Dodaje pustą sekcję na koniec kolekcji. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Zwraca indeks określonej sekcji w kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie sekcje z kolekcji. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Pobiera element o podanym indeksie. Tylko do odczytu [ISection](../../com.aspose.slides/isection).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Dodaje nową sekcję rozpoczynającą się od określonego slajdu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Pierwszy slajd sekcji |

**Zwraca:**
[ISection](../../com.aspose.slides/isection) - Added section.

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Dodaje pustą sekcję na określonej pozycji w kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |
| index | int | Indeks nowej sekcji. |

**Zwraca:**
[ISection](../../com.aspose.slides/isection) - Added section.

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Usuwa sekcję oraz slajdy znajdujące się w tej sekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do usunięcia z kolekcji. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Usuwa sekcję. Slajdy znajdujące się w tej sekcji zostaną połączone z poprzednią sekcją.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do usunięcia z kolekcji. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Przenosi sekcję i jej slajdy z kolekcji na określoną pozycję.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do przeniesienia. |
| index | int | Docelowy indeks. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Dodaje pustą sekcję na koniec kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nazwa sekcji |

**Zwraca:**
[ISection](../../com.aspose.slides/isection) - Added section.

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Zwraca indeks określonej sekcji w kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja do znalezienia. |

**Zwraca:**
int - Indeks sekcji lub -1, jeśli sekcja nie pochodzi z tej kolekcji.

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie sekcje z kolekcji.