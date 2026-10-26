---
title: ISectionCollection
second_title: Aspose.Slides Android számára Java API Referencia
description: Szektiók gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/isectioncollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

A szekciók gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Új szekciót ad hozzá, amely egy adott diától kezdődik. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Üres szekciót ad a gyűjtemény megadott pozíciójához. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Eltávolítja a szekciót és a szekcióban lévő diákat. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Eltávolítja a szekciót. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Áthelyezi a szekciót és diáit a gyűjteményből a megadott pozícióba. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Üres szekciót ad a gyűjtemény végéhez. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Az adott szekció indexét adja vissza a gyűjteményben. |
| [clear()](#clear--) | Eltávolítja az összes szekciót a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [ISection](../../com.aspose.slides/isection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Új szekciót ad hozzá, amely egy adott diától kezdődik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | A szekció első diája |

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection) - Hozzáadott szekció.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Üres szekciót ad a gyűjtemény megadott pozíciójához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |
| index | int | Az új szekció indexe. |

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection) - Hozzáadott szekció.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Eltávolítja a szekciót és a szekcióban lévő diákat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Az eltávolítandó szekció a gyűjteményből. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Eltávolítja a szekciót. A szekcióban lévő diák az előző szekcióval egyesülnek.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Az eltávolítandó szekció a gyűjteményből. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Áthelyezi a szekciót és diáit a gyűjteményből a megadott pozícióba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Áthelyezendő szekció. |
| index | int | Cél index. |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Üres szekciót ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |

**Visszatérési érték:**
[ISection](../../com.aspose.slides/isection) - Hozzáadott szekció.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Az adott szekció indexét adja vissza a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A keresendő szekció. |

**Visszatérési érték:**
int - A szekció indexe vagy -1, ha a szekció nem ebben a gyűjteményben van.
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes szekciót a gyűjteményből.