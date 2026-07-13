---
title: IMasterSlideCollection
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje kolekcję slajdów głównych.
type: docs
url: /pl/com.aspose.slides/imasterslidecollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Reprezentuje kolekcję slajdów głównych.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie z kolekcji. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Usuwa nieużywane slajdy główne. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Dodaje kopię określonego slajdu głównego na koniec kolekcji. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Wstawia kopię określonego slajdu głównego na wskazaną pozycję w kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Pobiera element o podanym indeksie. Tylko do odczytu [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd główny do usunięcia z kolekcji. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element o podanym indeksie z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Usuwa nieużywane slajdy główne.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| ignorePreserveField | boolean | Określa, czy ta metoda powinna usuwać nieużywane slajdy główne, nawet jeśli jej [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) właściwość jest ustawiona na true. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Dodaje kopię określonego slajdu głównego na koniec kolekcji. Powiązane slajdy układu zostaną również skopiowane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd do sklonowania. |

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Dodany slajd.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Wstawia kopię określonego slajdu głównego na wskazaną pozycję w kolekcji. Powiązane slajdy układu zostaną również skopiowane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd do sklonowania. |

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Wstawiony slajd główny.