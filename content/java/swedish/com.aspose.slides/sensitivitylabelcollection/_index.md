---
title: SensitivityLabelCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av känslighetsetiketter som tillämpas på dokumentet.
type: docs
url: /sv/com.aspose.slides/sensitivitylabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Representerar en samling av känslighetsetiketter som tillämpas på dokumentet.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar känslighetsetiketten efter index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Lägger till känslighetsetiketten i slutet av samlingen. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Lägger till en SensitivityLabel i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort känslighetsetiketten på angivet index. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [getCount()](#getCount--) | Returnerar antalet element i samlingen. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Kopierar alla element från samlingen till den angivna arrayen. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Returnerar känslighetsetiketten efter index.

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Lägger till känslighetsetiketten i slutet av samlingen.

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | java.lang.String | Id för känslighetsetiketten. |
| siteId | java.util.UUID | Azure Active Directory (Azure AD)-platsidentifieraren. |
| isEnabled | boolean | Flagga som indikerar om känslighetsetiketten är aktiverad. |
| methodType | int | Tilldelningsmetoden för känslighetsetiketten. |

**Returnerar:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Lägger till en SensitivityLabel i samlingen.

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | SensitivityLabel-objektet som ska läggas till i slutet av samlingen. |

**Returnerar:**
int – Indexet där SensitivityLabel lades till.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort känslighetsetiketten på angivet index.

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den känslighetsetikett som ska tas bort. |

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla element från samlingen.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> – En System.Collections.Generic.IEnumerator1 som kan användas för att iterera genom samlingen.
### getCount() {#getCount--}
```
public final int getCount()
```


Returnerar antalet element i samlingen. Skrivskyddad int .

**Returnerar:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Kopierar alla element från samlingen till den angivna arrayen.

**Parameterar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Målarray. |
| index | int | Startindex i målarrayen. |