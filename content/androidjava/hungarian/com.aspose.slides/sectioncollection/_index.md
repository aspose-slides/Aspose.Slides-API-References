---
title: SectionCollection
second_title: Aspose.Slides Androidhoz Java API referencia
description: A szekciók gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/sectioncollection/
---
**Öröklés:**  
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**  
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)  
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Székciók gyűjteményét képviseli.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexnél. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Diák szekciót ad hozzá, amely egy adott diától kezdődik. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Üres szekciót ad a gyűjtemény végéhez. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Üres szekciót ad a gyűjtemény megadott pozíciójába. |
| [size()](#size--) | Lekéri a gyűjteményben ténylegesen található elemek számát. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Visszaadja a megadott szekció indexét a gyűjteményben. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Eltávolítja a szekciót és a szekcióban lévő diákat. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Eltávolítja a szekciót. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Áthelyezi a szekciót és a hozzá tartozó diákat a gyűjteményből a megadott pozícióba. |
| [clear()](#clear--) | Eltávolítja az összes szekciót a gyűjteményből. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a teljes gyűjteményt a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |

### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Lekéri az elemet a megadott indexnél. Csak olvasható [ISection](../../com.aspose.slides/isection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Diák szekciót ad hozzá, amely egy adott diától kezdődik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | A szekció első diája |

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection) – Hozzáadott szekció.

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Üres szekciót ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection) – Hozzáadott szekció.

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Üres szekciót ad a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |
| index | int | Az új szekció indexe. |

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection) – Hozzáadott szekció.

### size() {#size--}
```
public final int size()
```

Lekéri a gyűjteményben ténylegesen található elemek számát. Csak olvasható int.

**Visszatérési érték:**
int

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Visszaadja a megadott szekció indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A keresett szekció. |

**Visszatérési érték:**
int – A szekció indexe vagy -1, ha a szekció nem ebből a gyűjteményből származik.

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Eltávolítja a szekciót és a szekcióban lévő diákat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A gyűjteményből eltávolítandó szekció. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Eltávolítja a szekciót. A szekcióban lévő diákat az előző szekcióba fogja egyesíteni.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A gyűjteményből eltávolítandó szekció. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Áthelyezi a szekciót és a hozzá tartozó diákat a gyűjteményből a megadott pozícióba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Áthelyezendő szekció. |
| index | int | Cél index. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes szekciót a gyűjteményből.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a teljes gyűjteményt a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb |
| index | int | Az index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - A IGenericEnumerator amely a gyűjteményen történő iteráláshoz használható.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Egy java.util.Iterator a teljes gyűjteményhez.