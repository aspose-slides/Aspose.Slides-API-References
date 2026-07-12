---
title: ISensitivityLabel
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Reprezentálja a Microsoft Purview Information Protection szenzitivitási címkét.
type: docs
url: /hu/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Reprezentálja a Microsoft Purview Information Protection szenzitivitási címkét.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getId()](#getId--) | Visszaadja vagy beállítja a szenzitivitási címke azonosítóját. |
| [setId(String value)](#setId-java.lang.String-) | Visszaadja vagy beállítja a szenzitivitási címke azonosítóját. |
| [getSiteId()](#getSiteId--) | Visszaadja vagy beállítja az Azure Active Directory (Azure AD) webhelyazonosítót, amely a szenzitivitási címke irányelvéhez tartozik, és leírja a szenzitivitási címkét. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Visszaadja vagy beállítja az Azure Active Directory (Azure AD) webhelyazonosítót, amely a szenzitivitási címke irányelvéhez tartozik, és leírja a szenzitivitási címkét. |
| [isEnabled()](#isEnabled--) | Jelzi, hogy a szenzitivitási címke engedélyezve van-e. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Jelzi, hogy a szenzitivitási címke engedélyezve van-e. |
| [isRemoved()](#isRemoved--) | Jelzi, hogy a szenzitivitási címkét eltávolították-e. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Jelzi, hogy a szenzitivitási címkét eltávolították-e. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Visszaadja vagy beállítja a szenzitivitási címke hozzárendelési módját. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Visszaadja vagy beállítja a szenzitivitási címke hozzárendelési módját. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Visszaadja a fájlra alkalmazandó tartalomjelölési típusok listáját. |
### getId() {#getId--}
```
public abstract String getId()
```


Visszaadja vagy beállítja a szenzitivitási címke azonosítóját. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Visszaadja vagy beállítja a szenzitivitási címke azonosítóját. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Visszaadja vagy beállítja az Azure Active Directory (Azure AD) webhelyazonosítót, amely a szenzitivitási címke irányelvéhez tartozik, és leírja a szenzitivitási címkét. Olvasás/írás java.util.UUID.

**Visszatérési érték:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Visszaadja vagy beállítja az Azure Active Directory (Azure AD) webhelyazonosítót, amely a szenzitivitási címke irányelvéhez tartozik, és leírja a szenzitivitási címkét. Olvasás/írás java.util.UUID.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Jelzi, hogy a szenzitivitási címke engedélyezve van-e.

**Visszatérési érték:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Jelzi, hogy a szenzitivitási címke engedélyezve van-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Jelzi, hogy a szenzitivitási címkét eltávolították-e.

**Visszatérési érték:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Jelzi, hogy a szenzitivitási címkét eltávolították-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Visszaadja vagy beállítja a szenzitivitási címke hozzárendelési módját. Olvasás/írás [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Visszatérési érték:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Visszaadja vagy beállítja a szenzitivitási címke hozzárendelési módját. Olvasás/írás [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Visszaadja a fájlra alkalmazandó tartalomjelölési típusok listáját.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A tartalomtípusok listája [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)