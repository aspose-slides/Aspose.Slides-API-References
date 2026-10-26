---
title: CustomXmlPartCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av anpassade xml-delar.
type: docs
url: /sv/com.aspose.slides/customxmlpartcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Representerar en samling av anpassade xml-delar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar elementet på det angivna indexet. |
| [size()](#size--) | Returnerar antalet anpassade xml-delar i samlingen. |
| [add(String xmlString)](#add-java.lang.String-) | Lägger till en ny anpassad xml-del. |
| [add(byte[] xmlData)](#add-byte---) | Lägger till en ny anpassad xml-del. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Lägger till en ny anpassad xml-del. |
| [removeAt(int index)](#removeAt-int-) | Tar bort den anpassade xml-delen på det angivna indexet. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [clear()](#clear--) | Tar bort alla objekt från samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar till angiven array. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Returnerar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det noll-baserade indexet för elementet som ska hämtas. |

**Returnerar:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Elementet på det angivna indexet.

### size() {#size--}
```
public final int size()
```

Returnerar antalet anpassade xml-delar i samlingen. Skrivskyddad int.

**Returnerar:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Lägger till en ny anpassad xml-del.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlString | java.lang.String | XML-strängen för den nya delen som ska läggas till. |

**Returnerar:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Skapad anpassad xml-del.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Lägger till en ny anpassad xml-del.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlData | byte[] | XML-data för den nya delen som ska läggas till. |

**Returnerar:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Skapad anpassad xml-del.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Lägger till en ny anpassad xml-del.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream med XML-data för den nya delen som ska läggas till. |

**Returnerar:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Skapad anpassad xml-del.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort den anpassade xml-delen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det noll-baserade indexet för elementet som ska tas bort. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Den anpassade xml-delen som ska tas bort. |

**Returnerar:**
boolean - true om objektet avlägsnas framgångsrikt; annars false.

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla objekt från samlingen.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar till angiven array.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array att kopiera till. |
| index | int | Index att börja kopiera från. |

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
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - En IGenericEnumerator som kan användas för att iterera genom samlingen.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - En java.util.Iterator för hela samlingen.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject