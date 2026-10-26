---
title: MasterSlideCollection
second_title: Aspose.Slides dla Java - Referencja API
description: Reprezentuje kolekcję slajdów master.
type: docs
url: /pl/com.aspose.slides/masterslidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Reprezentuje zbiór slajdów master.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Pobiera liczbę elementów faktycznie zawartych w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie w kolekcji. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Usuwa nieużywane slajdy master. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Dodaje kopię określonego slajdu master na koniec kolekcji. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Wstawia kopię określonego slajdu master na wskazaną pozycję w kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo-bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca obiekt synchronizacji. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Javy dla całej kolekcji. |
### size() {#size--}
```
public final int size()
```

Pobiera liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Pobiera element o podanym indeksie. Tylko do odczytu [MasterSlide](../../com.aspose.slides/masterslide).

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

Usuwa element o podanym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. 

--------------------

Aby uniknąć rzucenia PptxEditException, przed wywołaniem sprawdź właściwość HasDependingSlides slajdu master. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Usuwa nieużywane slajdy master.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| ignorePreserveField | boolean | Określa, czy metoda ma usuwać nieużywany master, nawet jeśli jego właściwość [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) jest ustawiona na true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Dodaje kopię określonego slajdu master na koniec kolekcji. Powiązane slajdy układu zostaną również skopiowane.

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

Wstawia kopię określonego slajdu master na wskazaną pozycję w kolekcji. Powiązane slajdy układu zostaną również skopiowane.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Utwórz klasę Presentation, aby wczytać plik prezentacji źródłowej
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Utwórz klasę Presentation dla prezentacji docelowej (gdzie slajd ma być sklonowany)
>      Presentation destPres = new Presentation();
>      try {
>          // Utwórz ISlide z kolekcji slajdów w prezentacji źródłowej wraz z
>          // Slajdem master
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Pobierz slajdy Master prezentacji docelowej
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
| index | int | Indeks początkowy w tablicy docelowej. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo-bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca obiekt synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Zwraca enumerator iterujący po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - IGenericEnumerator, który może być używany do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Zwraca iterator Javy dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - java.util.Iterator dla całej kolekcji.