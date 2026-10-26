---
title: VbaModuleCollection
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Reprezentuje kolekci modulů VBA projektu.
type: docs
url: /cs/com.aspose.slides/vbamodulecollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Reprezentuje kolekci modulů VBA projektu.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrátí počet prvků skutečně obsažených v kolekci. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Přidá nový prázdný modul do projektu VBA. |
| [get_Item(int index)](#get-Item-int-) | Vrátí prvek na zadaném indexu. |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrátí hodnotu, která určuje, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrátí kořen synchronizace. |
### size() {#size--}
```
public final int size()
```

Vrátí počet prvků skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

Odstraní první výskyt konkrétního objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Modul, který se má odebrat z kolekce. |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

Přidá nový prázdný modul do projektu VBA.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název modulu |

**Vrací:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Přidaný modul.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

Vrátí prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

Vrátí enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

Vrátí java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - java.util.Iterator pro celou kolekci.
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

Vrátí hodnotu, která určuje, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrátí kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object