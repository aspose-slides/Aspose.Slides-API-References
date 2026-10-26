---
title: EffectStyleCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje kolekci stylů efektů.
type: docs
url: /cs/com.aspose.slides/effectstylecollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

Představuje kolekci stylů efektů.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na zadané pozici. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [size()](#size--) | Vrací počet prvků v kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu udávající, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```


Vrací prvek na zadané pozici. Pouze ke čtení [EffectStyle](../../com.aspose.slides/effectstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice prvku. |

**Vrací:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - Prvek na zadané pozici.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - java.util.Iterator pro celou kolekci.
### size() {#size--}
```
public final int size()
```


Vrací počet prvků v kolekci. Pouze ke čtení int, Pouze ke čtení int.

**Vrací:**
int
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


Vrací hodnotu udávající, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object