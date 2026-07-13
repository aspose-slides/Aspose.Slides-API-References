---
title: ITagCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar samlingen av taggar, användardefinierade strängpar
type: docs
url: /sv/com.aspose.slides/itagcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Representerar samlingen av taggar (användardefinierade par av strängar)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Lägger till en ny tagg i samlingen. |
| [remove(String name)](#remove-java.lang.String-) | Tar bort taggen med ett angivet namn från samlingen. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Returnerar det nollbaserade indexet för den angivna nyckeln i samlingen. |
| [contains(String name)](#contains-java.lang.String-) | Avgör om samlingen innehåller ett specifikt namn. |
| [removeAt(int index)](#removeAt-int-) | Tar bort taggen på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla taggar från samlingen. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Returnerar värdet för en tagg på det angivna indexet. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Returnerar nyckeln för en tagg på det angivna indexet. |
| [getNamesOfTags()](#getNamesOfTags--) | Returnerar namn på taggarna. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returnerar eller sätter ett nyckel-värdepar för en tagg. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returnerar eller sätter ett nyckel-värdepar för en tagg. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Lägger till en ny tagg i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på taggen. |
| value | java.lang.String | Värdet på taggen. |

**Returnerar:**
int - Indexet för den tillagda taggen.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Tar bort taggen med ett angivet namn från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på taggen som ska tas bort. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Returnerar det nollbaserade indexet för den angivna nyckeln i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet att söka i samlingen. |

**Returnerar:**
int - Det nollbaserade indexet för nyckeln, om nyckeln finns i samlingen; annars -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Avgör om samlingen innehåller ett specifikt namn.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Nyckeln att söka. |

**Returnerar:**
boolean - Sant om samlingen innehåller en tagg med den angivna nyckeln; annars falskt.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort taggen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för taggen som ska tas bort. |
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla taggar från samlingen.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Returnerar värdet för en tagg på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en tagg att returnera. |

**Returnerar:**
java.lang.String - Värdet för en tagg.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Returnerar nyckeln för en tagg på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en tagg att returnera. |

**Returnerar:**
java.lang.String - Nyckeln för en tagg.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Returnerar namn på taggarna.

**Returnerar:**
java.lang.String[] - Namnen på taggarna.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Returnerar eller sätter ett nyckel-värdepar för en tagg.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Nyckeln för en tagg. |

**Returnerar:**
java.lang.String - Värdet för en tagg.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Returnerar eller sätter ett nyckel-värdepar för en tagg.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Nyckeln för en tagg. |
| value | java.lang.String |  |