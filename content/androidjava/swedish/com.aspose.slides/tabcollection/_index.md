---
title: TabCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av flikar.
type: docs
url: /sv/com.aspose.slides/tabcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Representerar en samling av tabs.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [add(double position, int align)](#add-double-int-) | Lägger till en Tab i samlingen. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Lägger till en Tab i samlingen. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om två TabsEx-instanser är lika. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som visar om åtkomsten till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
### size() {#size--}
```
public final int size()
```


Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Hämtar elementet på det angivna indexet. Skrivskyddad [Tab](../../com.aspose.slides/tab).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


Lägger till en Tab i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Returnerar:**
[ITab](../../com.aspose.slides/itab) - Tillagd tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


Lägger till en Tab i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Tab-objektet som ska läggas till i slutet av samlingen. |

**Returnerar:**
int - Indexet där tabben lades till.
### clear() {#clear--}
```
public final void clear()
```


Tar bort alla element från samlingen.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet att ta bort. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om två TabsEx-instanser är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx att jämföra med den aktuella TabsEx. |

**Returnerar:**
boolean - **true** om den angivna TabsEx är lika med den aktuella TabsEx; annars, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i målarrayen. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object