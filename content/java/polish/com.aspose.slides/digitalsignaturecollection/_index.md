---
title: DigitalSignatureCollection
second_title: Aspose.Slides dla Java - dokumentacja API
description: Reprezentuje kolekcję podpisów cyfrowych dołączonych do dokumentu.
type: docs
url: /pl/com.aspose.slides/digitalsignaturecollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

Reprezentuje kolekcję podpisów cyfrowych dołączonych do dokumentu.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca podpis według indeksu. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | Dodaje podpis na końcu kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa podpis pod wskazanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie podpisy z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
| [size()](#size--) | Zwraca liczbę elementów w kolekcji. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo-bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

Zwraca podpis według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

Dodaje podpis na końcu kolekcji.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Podpis do dodania. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa podpis pod wskazanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks podpisu, który ma zostać usunięty. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie podpisy z kolekcji.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Enumerator IGenericEnumerator, który może być używany do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Iterator java.util.Iterator dla całej kolekcji.
### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo-bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object
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