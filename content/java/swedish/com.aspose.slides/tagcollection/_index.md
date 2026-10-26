---
title: TagCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar samlingen av taggar, användardefinierade par av strängar
type: docs
url: /sv/com.aspose.slides/tagcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Representerar samlingen av taggar (användardefinierade par av strängar)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar ett antal taggar i samlingen. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Lägger till en ny tagg i samlingen. |
| [remove(String name)](#remove-java.lang.String-) | Tar bort taggen med ett specificerat namn från samlingen. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Returnerar det nollbaserade indexet för den angivna nyckeln i samlingen. |
| [contains(String name)](#contains-java.lang.String-) | Avgör om samlingen innehåller ett specifikt namn. |
| [removeAt(int index)](#removeAt-int-) | Tar bort taggen på det specifika indexet. |
| [clear()](#clear--) | Tar bort alla taggar från samlingen. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Returnerar värdet för en tagg på det angivna indexet. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Returnerar nyckeln för en tagg på det angivna indexet. |
| [getNamesOfTags()](#getNamesOfTags--) | Returnerar namn på taggar. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returnerar eller anger ett nyckel- och värdepar för en tagg. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returnerar eller anger ett nyckel- och värdepar för en tagg. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en uppräknare som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### size() {#size--}
```
public final int size()
```

Returnerar ett antal taggar i samlingen. Skrivskyddad int.

**Returnerar:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Lägger till en ny tagg i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Taggens namn. |
| value | java.lang.String | Taggens värde. |

**Returnerar:**
int - Index för den tillagda taggen.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Tar bort taggen med ett specificerat namn från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på taggen som ska tas bort. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Returnerar det nollbaserade indexet för den angivna nyckeln i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet att söka efter i samlingen. |

**Returnerar:**
int - Det nollbaserade indexet för nyckeln, om nyckeln finns i samlingen; annars -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Avgör om samlingen innehåller ett specifikt namn.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Nyckeln att söka efter. |

**Returnerar:**
boolean - Sant om samlingen innehåller en tagg med den angivna nyckeln; annars falskt.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort taggen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för taggen som ska tas bort. |
### clear() {#clear--}
```
public final void clear()
```

Tar bort alla taggar från samlingen.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Returnerar värdet för en tagg på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för taggen som ska returneras. |

**Returnerar:**
java.lang.String - Värdet för en tagg.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Returnerar nyckeln för en tagg på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för taggen som ska returneras. |

**Returnerar:**
java.lang.String - Nyckeln för en tagg.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Returnerar namn på taggar.

**Returnerar:**
java.lang.String[] - Namn på taggar.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Returnerar eller anger ett nyckel- och värdepar för en tagg.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Nyckeln för en tagg. |

**Returnerar:**
java.lang.String - Värdet för en tagg.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Returnerar eller anger ett nyckel- och värdepar för en tagg.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Nyckeln för en tagg. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array att fylla. |
| index | int | Startposition i målarrayen. |
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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Returnerar en uppräknare som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.