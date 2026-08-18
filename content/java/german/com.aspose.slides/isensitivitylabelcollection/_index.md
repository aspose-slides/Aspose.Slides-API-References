---
title: ISensitivityLabelCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Sensitivitätslabels dar, die auf das Dokument angewendet wurden.
type: docs
url: /de/com.aspose.slides/isensitivitylabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Stellt eine Sammlung von Sensitivitätslabels dar, die auf das Dokument angewendet wurden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Sensitivitätslabel anhand des Index zurück. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Fügt das Sensitivitätslabel am Ende der Sammlung hinzu. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Fügt ein SensitivityLabel zur Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Sensitivitätslabel am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [getCount()](#getCount--) | Gibt die Anzahl aller Elemente in der Sammlung zurück. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


Gibt das Sensitivitätslabel anhand des Index zurück. Nur lesend [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Fügt das Sensitivitätslabel am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | java.lang.String | Die ID des Sensitivitätslabels. |
| siteId | java.util.UUID | Der Azure Active Directory (Azure AD)-Site-Bezeichner. |
| isEnabled | boolean | Flag gibt an, ob das Sensitivitätslabel aktiviert ist. |
| methodType | int | Die Zuweisungsmethode für das Sensitivitätslabel. |

**Rückgabewert:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


Fügt ein SensitivityLabel zur Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Das SensitivityLabel-Objekt, das am Ende der Sammlung hinzugefügt werden soll. |

**Rückgabewert:**
int - Der Index, an dem das SensitivityLabel hinzugefügt wurde.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt das Sensitivitätslabel am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- |
| index | int | Index des Sensitivitätslabels, das gelöscht werden soll. |
### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Elemente aus der Sammlung.
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gibt die Anzahl aller Elemente in der Sammlung zurück. Nur lesend  int .

**Rückgabewert:**
int