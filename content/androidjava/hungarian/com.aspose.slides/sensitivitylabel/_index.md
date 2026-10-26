---
title: SensitivityLabel
second_title: Aspose.Slides Androidra a Java API hivatkozással
description: A Microsoft Purview Information Protection érzékenységi címkét képviseli.
type: docs
url: /hu/com.aspose.slides/sensitivitylabel/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

A Microsoft Purview Information Protection érzékenységi címkét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getId()](#getId--) | Visszaadja vagy beállítja az érzékenységi címke azonosítóját. |
| [setId(String value)](#setId-java.lang.String-) | Visszaadja vagy beállítja az érzékenységi címke azonosítóját. |
| [getSiteId()](#getSiteId--) | Visszaadja vagy beállítja az Azure Active Directory (Azure AD) webhelyazonosítót, amely a leíró érzékenységi címke szabályzathoz tartozik. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Visszaadja vagy beállítja az Azure Active Directory (Azure AD) webhelyazonosítót, amely a leíró érzékenységi címke szabályzathoz tartozik. |
| [isEnabled()](#isEnabled--) | Jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| [isRemoved()](#isRemoved--) | Jelzi, hogy az érzékenységi címke eltávolításra került-e. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Jelzi, hogy az érzékenységi címke eltávolításra került-e. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Visszaadja vagy beállítja az érzékenységi címke hozzárendelési módszerét. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Visszaadja vagy beállítja az érzékenységi címke hozzárendelési módszerét. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Visszaadja a fájlra alkalmazandó tartalomjelölés típusainak listáját. |
### getId() {#getId--}
```
public final String getId()
```

Visszaadja vagy beállítja az érzékenységi címke azonosítóját. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Visszaadja vagy beállítja az érzékenységi címke azonosítóját. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Visszaadja vagy beállítja az Azure Active Directory (Azure AD) webhelyazonosítót, amely a leíró érzékenységi címke szabályzathoz tartozik. Olvasás/írás java.util.UUID.

**Visszatér:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Visszaadja vagy beállítja az Azure Active Directory (Azure AD) webhelyazonosítót, amely a leíró érzékenységi címke szabályzathoz tartozik. Olvasás/írás java.util.UUID.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Jelzi, hogy az érzékenységi címke engedélyezve van-e.

**Visszatér:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Jelzi, hogy az érzékenységi címke engedélyezve van-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Jelzi, hogy az érzékenységi címke eltávolításra került-e.

**Visszatér:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Jelzi, hogy az érzékenységi címke eltávolításra került-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Visszaadja vagy beállítja az érzékenységi címke hozzárendelési módszerét. Olvasás/írás [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Visszatér:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Visszaadja vagy beállítja az érzékenységi címke hozzárendelési módszerét. Olvasás/írás [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Visszaadja a fájlra alkalmazandó tartalomjelölés típusainak listáját.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A tartalomtípusok listája [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)