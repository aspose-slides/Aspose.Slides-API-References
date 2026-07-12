---
title: SensitivityLabelCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Sensitivitätsbezeichnungen dar, die auf das Dokument angewendet werden.
type: docs
url: /de/com.aspose.slides/sensitivitylabelcollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Stellt eine Sammlung von Sensitivitätsbezeichnungen dar, die auf das Dokument angewendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Sensitivitätsbezeichnung am Index zurück. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Fügt die Sensitivitätsbezeichnung am Ende der Sammlung hinzu. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Fügt ein SensitivityLabel zur Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Sensitivitätsbezeichnung am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [getCount()](#getCount--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

Gibt die Sensitivitätsbezeichnung am Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Fügt die Sensitivitätsbezeichnung am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | java.lang.String | Die ID der Sensitivitätsbezeichnung. |
| siteId | java.util.UUID | Der Azure Active Directory (Azure AD) Standortidentifikator. |
| isEnabled | boolean | Flag gibt an, ob die Sensitivitätsbezeichnung aktiviert ist. |
| methodType | int | Die Zuweisungsmethode für die Sensitivitätsbezeichnung. |

**Rückgabewert:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

Fügt ein SensitivityLabel zur Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Das SensitivityLabel-Objekt, das am Ende der Sammlung hinzugefügt wird. |

**Rückgabewert:**
int - Der Index, an dem das SensitivityLabel hinzugefügt wurde.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt die Sensitivitätsbezeichnung am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zu löschenden Sensitivitätsbezeichnung. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus der Sammlung.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Ein System.Collections.Generic.IEnumerator1, der zum Durchlaufen der Sammlung verwendet werden kann.
### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die Anzahl der Elemente in der Sammlung zurück. Nur-Lesen  int .

**Rückgabewert:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |