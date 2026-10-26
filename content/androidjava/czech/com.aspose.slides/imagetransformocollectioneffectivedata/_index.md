---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Neměnný objekt, který představuje kolekci jen pro čtení efektivních transformací obrazu.
type: docs
url: /cs/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

Neměnný objekt, který představuje kolekci jen pro čtení efektivních transformací obrazu.

--------------------

Název IImageTransformOperationCollectionEffectiveData byl zkrácen na IImageTransformOCollectionEffectiveData, protože délka názvů COM nesmí být delší než 39.
## Konstruktoři

| Konstruktor | Popis |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet efektů obrázku ve sbírce. |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek podle indexu. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný objekt roven aktuálnímu objektu. |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hashovací tabulka. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje všechny prvky ze sbírky do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


Vrací počet efektů obrázku ve sbírce. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


Vrací prvek podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku. |

**Vrací:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - Objekt [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda je zadaný objekt roven aktuálnímu objektu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt, který se má porovnat s aktuálním objektem. |

**Vrací:**
boolean - true, pokud je zadaný objekt roven aktuálnímu objektu; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hashovací tabulka.

**Vrací:**
int - hash kód pro aktuální objekt.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopíruje všechny prvky ze sbírky do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole, které se má naplnit. |
| index | int | Počáteční pozice v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object