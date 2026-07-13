---
title: MasterSlideCollection
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje kolekcję slajdów master.
type: docs
url: /pl/com.aspose.slides/masterslidecollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Reprezentuje kolekcję slajdów master.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę elementów rzeczywiście zawartych w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element pod określonym indeksem. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod określonym indeksem w kolekcji. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Usuwa nieużywane slajdy master. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Dodaje kopię określonego slajdu master na koniec kolekcji. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Wstawia kopię określonego slajdu master na wskazane miejsce w kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów rzeczywiście zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Zwraca element pod określonym indeksem. Tylko do odczytu [MasterSlide](../../com.aspose.slides/masterslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd master do usunięcia z kolekcji. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa element pod określonym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

--------------------

Aby uniknąć rzucenia PptxEditException, przedtem sprawdź właściwość HasDependingSlides mastera. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Usuwa nieużywane slajdy master.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| ignorePreserveField | boolean | Określa, czy ta metoda powinna usuwać nieużywane mastery nawet jeśli ich właściwość [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) jest ustawiona na true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Dodaje kopię określonego slajdu master na koniec kolekcji. Połączone slajdy układu także zostaną skopiowane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd do sklonowania. |

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Dodany slajd.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Wstawia kopię określonego slajdu master na wskazane miejsce w kolekcji. Połączone slajdy układu także zostaną skopiowane.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Utwórz instancję klasy Presentation, aby załadować plik prezentacji źródłowej
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Utwórz instancję klasy Presentation dla prezentacji docelowej (gdzie slajd ma być sklonowany)
>      Presentation destPres = new Presentation();
>      try {
>          // Utwórz instancję ISlide z kolekcji slajdów w prezentacji źródłowej wraz z
>          // Slajdem master
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Pobierz slajdy master prezentacji docelowej
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Sklonuj żądany slajd master z prezentacji źródłowej do kolekcji masterów w
>          // Prezentacji docelowej
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Kolekcja slajdów w prezentacji docelowej
>          ISlideCollection slds = destPres.getSlides();
>          // Sklonuj slajd źródłowy do kolekcji slajdów docelowych.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Zapisz prezentację docelową na dysku
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd do sklonowania. |

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Wstawiony slajd master.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

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
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - An java.util.Iterator for the entire collection.