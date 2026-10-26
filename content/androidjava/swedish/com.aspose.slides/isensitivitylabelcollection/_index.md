---
title: ISensitivityLabelCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av känslighetsetiketter som tillämpas på dokumentet.
type: docs
url: /sv/com.aspose.slides/isensitivitylabelcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
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
| [getCount()](#getCount--) | Hämtar antalet element i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Returnerar känslighetsetiketten efter index. Skrivskyddad [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Lägger till känslighetsetiketten i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | java.lang.String | Id för känslighetsetiketten. |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) webbplatsidentifieraren. |
| isEnabled | boolean | Flaggan indikerar om känslighetsetiketten är aktiverad. |
| methodType | int | Tilldelningsmetoden för känslighetsetiketten. |

**Returnerar:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Lägger till en SensitivityLabel i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | SensitivityLabel-objektet som ska läggas till i slutet av samlingen. |

**Returnerar:**
int - Indexet där SensitivityLabel lades till.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort känslighetsetiketten på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den känslighetsetikett som ska tas bort. |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element från samlingen.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Hämtar antalet element i samlingen. Skrivskyddad  int .

**Returnerar:**
int