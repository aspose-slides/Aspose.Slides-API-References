---
title: ISectionCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci sekcí.
type: docs
url: /cs/com.aspose.slides/isectioncollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Reprezentuje kolekci sekcí.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Přidá novou sekci, která začíná od konkrétního snímku. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Přidá prázdnou sekci na určenou pozici ve sbírce. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Odstraní sekci a snímky obsažené v sekci. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Odstraní sekci. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Přesune sekci a její snímky ze sbírky na zadanou pozici. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Přidá prázdnou sekci na konec sbírky. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Vrací index zadané sekce ve sbírce. |
| [clear()](#clear--) | Odstraní všechny sekce ze sbírky. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [ISection](../../com.aspose.slides/isection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Přidá novou sekci, která začíná od konkrétního snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název sekce |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | První snímek sekce |

**Návratová hodnota:**
[ISection](../../com.aspose.slides/isection) - Přidaná sekce.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Přidá prázdnou sekci na určenou pozici ve sbírce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název sekce |
| index | int | Index nové sekce. |

**Návratová hodnota:**
[ISection](../../com.aspose.slides/isection) - Přidaná sekce.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Odstraní sekci a snímky obsažené v sekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce, která má být odstraněna ze sbírky. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Odstraní sekci. Snímky obsažené v sekci budou sloučeny s předchozí sekcí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce, která má být odstraněna ze sbírky. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Přesune sekci a její snímky ze sbírky na zadanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce k přesunu. |
| index | int | Cílový index. |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Přidá prázdnou sekci na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název sekce |

**Návratová hodnota:**
[ISection](../../com.aspose.slides/isection) - Přidaná sekce.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Vrací index zadané sekce ve sbírce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sekce k vyhledání. |

**Návratová hodnota:**
int - Index sekce nebo -1, pokud sekce nepatří do této sbírky.
### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny sekce ze sbírky.