---
title: SectionCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje kolekci sekcí.
type: docs
url: /cs/com.aspose.slides/sectioncollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Představuje kolekci sekcí.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Přidá sekci snímků začínající od konkrétního snímku. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Přidá prázdnou sekci na konec kolekce. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Přidá prázdnou sekci na určenou pozici v kolekci. |
| [size()](#size--) | Získá počet prvků skutečně obsažených v kolekci. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Vrátí index zadané sekce v kolekci. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Odstraní sekci a snímky obsažené v sekci. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Odstraní sekci. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Přesune sekci a její snímky z kolekce na určenou pozici. |
| [clear()](#clear--) | Odstraní všechny sekce z kolekce. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje celou kolekci do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrátí hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrátí synchronizační kořen. |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [ISection](../../com.aspose.slides/isection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Přidá sekci snímků začínající od konkrétního snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název sekce |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | První snímek sekce |

**Vrací:**
[ISection](../../com.aspose.slides/isection) - Přidaná sekce.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Přidá prázdnou sekci na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název sekce |

**Vrací:**
[ISection](../../com.aspose.slides/isection) - Přidaná sekce.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Přidá prázdnou sekci na určenou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název sekce |
| index | int | Index nové sekce. |

**Vrací:**
[ISection](../../com.aspose.slides/isection) - Přidaná sekce.
### size() {#size--}
```
public final int size()
```

Získá počet prvků skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Vrátí index zadané sekce v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce k nalezení. |

**Vrací:**
int - Index sekce nebo -1, pokud sekce není z této kolekce.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Odstraní sekci a snímky obsažené v sekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce, kterou je třeba odstranit z kolekce. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Odstraní sekci. Snímky obsažené v sekci budou sloučeny do předchozí sekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce, kterou je třeba odstranit z kolekce. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Přesune sekci a její snímky z kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce k přesunu. |
| index | int | Cílový index. |

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny sekce z kolekce.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje celou kolekci do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole |
| index | int | Index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrátí hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrátí synchronizační kořen. Pouze pro čtení Object.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Vrátí enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Vrátí java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - An java.util.Iterator for the entire collection.