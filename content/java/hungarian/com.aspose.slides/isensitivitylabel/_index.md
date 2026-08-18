---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /hu/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Az érzékenységi címkét reprezentálja a Microsoft Purview Information Protection-ből.
## Módszerek

| Method | Leírás |
| --- | --- |
| [getId()](#getId--) | Visszatér vagy beállítja az érzékenységi címke azonosítóját. |
| [setId(String value)](#setId-java.lang.String-) | Visszatér vagy beállítja az érzékenységi címke azonosítóját. |
| [getSiteId()](#getSiteId--) | Visszatér vagy beállítja az Azure Active Directory (Azure AD) oldalazonosítót, amely a érzékenységi címkét leíró címkepolitikához tartozik. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Visszatér vagy beállítja az Azure Active Directory (Azure AD) oldalazonosítót, amely a érzékenységi címkét leíró címkepolitikához tartozik. |
| [isEnabled()](#isEnabled--) | Jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| [isRemoved()](#isRemoved--) | Jelzi, hogy az érzékenységi címke el lett-e távolítva. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Jelzi, hogy az érzékenységi címke el lett-e távolítva. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Visszatér vagy beállítja a hozzárendelési módszert az érzékenységi címkéhez. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Visszatér vagy beállítja a hozzárendelési módszert az érzékenységi címkéhez. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Visszaadja a fájlra alkalmazandó tartalomjelölés típusainak listáját. |
### getId() {#getId--}
```
public abstract String getId()
```


Visszatér vagy beállítja az érzékenységi címke azonosítóját. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Visszatér vagy beállítja az érzékenységi címke azonosítóját. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Visszatér vagy beállítja az Azure Active Directory (Azure AD) oldalazonosítót, amely a érzékenységi címkét leíró címkepolitikához tartozik. Olvasás/írás java.util.UUID.

**Visszatér:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Visszatér vagy beállítja az Azure Active Directory (Azure AD) oldalazonosítót, amely a érzékenységi címkét leíró címkepolitikához tartozik. Olvasás/írás java.util.UUID.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Jelzi, hogy az érzékenységi címke engedélyezve van-e.

**Visszatér:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Jelzi, hogy az érzékenységi címke engedélyezve van-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Jelzi, hogy az érzékenységi címke el lett-e távolítva.

**Visszatér:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Jelzi, hogy az érzékenységi címke el lett-e távolítva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Visszatér vagy beállítja a hozzárendelési módszert az érzékenységi címkéhez. Olvasás/írás [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Visszatér:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Visszatér vagy beállítja a hozzárendelési módszert az érzékenységi címkéhez. Olvasás/írás [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Visszaadja a fájlra alkalmazandó tartalomjelölés típusainak listáját.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A tartalomtípusok listája [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)