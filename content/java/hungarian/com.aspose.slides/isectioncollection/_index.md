---
title: ISectionCollection
second_title: Aspose.Slides Java API referenciája
description: A szekciók gyűjteményét képviseli.
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
| [get_Item(int index)](#get-Item-int-) | Megkapja az elemet a megadott indexen. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Új szekció hozzáadása, amely egy meghatározott diától kezdődik. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Üres szekció hozzáadása a gyűjtemény megadott pozíciójába. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Szekció és a szekcióban lévő diák eltávolítása. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Szekció eltávolítása. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Szekció és diái áthelyezése a gyűjteményből a megadott pozícióba. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Üres szekció hozzáadása a gyűjtemény végéhez. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Visszaadja a megadott szekció indexét a gyűjteményben. |
| [clear()](#clear--) | Eltávolítja az összes szekciót a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Megkapja az elemet a megadott indexen. Csak olvasható [ISection](../../com.aspose.slides/isection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Új szekció hozzáadása, amely egy meghatározott diától kezdődik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | A szekció első diaja |

**Visszatér:**
[ISection](../../com.aspose.slides/isection) - Hozzáadott szekció.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Üres szekció hozzáadása a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |
| index | int | Az új szekció indexe. |

**Visszatér:**
[ISection](../../com.aspose.slides/isection) - Hozzáadott szekció.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Szekció és a szekcióban lévő diák eltávolítása.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A gyűjteményből eltávolítandó szekció. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Szekció eltávolítása. A szekcióban lévő diák az előző szekcióba lesznek egyesítve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A gyűjteményből eltávolítandó szekció. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Szekció és diái áthelyezése a gyűjteményből a megadott pozícióba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Áthelyezendő szekció. |
| index | int | Cél index. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Üres szekció hozzáadása a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A szekció neve |

**Visszatér:**
[ISection](../../com.aspose.slides/isection) - Hozzáadott szekció.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Visszaadja a megadott szekció indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A megtalálandó szekció. |

**Visszatér:**
int - A szekció indexe vagy -1, ha a szekció nem ebben a gyűjteményben található.
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes szekciót a gyűjteményből.