---
title: AdjustValueCollection
second_title: Aspose.Slides pro Java – reference API
description: Představuje kolekci úprav tvarů.
type: docs
url: /cs/com.aspose.slides/adjustvaluecollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Představuje kolekci úprav tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet úprav. |
| [get_Item(int index)](#get-Item-int-) | Vrací úpravu podle indexu. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově zabezpečený). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor pro celou kolekci. |
### size() {#size--}
```
public final int size()
```

Vrací počet úprav. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

Vrací úpravu podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | index úpravy. |

**Vrací:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově zabezpečený). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

Vrací enumerátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.IEnumerator