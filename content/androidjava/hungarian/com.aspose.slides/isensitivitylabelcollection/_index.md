---
title: ISensitivityLabelCollection
second_title: Aspose.Slides Androidra a Java API-referencia
description: A dokumentumra alkalmazott érzékenységi címkék gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/isensitivitylabelcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

A dokumentumra alkalmazott érzékenységi címkék gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az index szerinti érzékenységi címkét. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Hozzáadja az érzékenységi címkét a gyűjtemény végéhez. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Hozzáad egy SensitivityLabel objektumot a gyűjteményhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az érzékenységi címkét a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben lévő összes elem számát. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Visszaadja az index szerinti érzékenységi címkét. Csak olvasható [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Hozzáadja az érzékenységi címkét a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | java.lang.String | Az érzékenységi címke azonosítója. |
| siteId | java.util.UUID | Az Azure Active Directory (Azure AD) helyazonosító. |
| isEnabled | boolean | A jelző, amely jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| methodType | int | Az érzékenységi címke hozzárendelési módja. |

**Visszatérési érték:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Hozzáad egy SensitivityLabel objektumot a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | A SensitivityLabel objektum, amely a gyűjtemény végére lesz hozzáadva. |

**Visszatérési érték:**
int - Az az index, ahol a SensitivityLabel hozzá lett adva.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja az érzékenységi címkét a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő érzékenységi címke indexe. |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes elemet a gyűjteményből.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lekéri a gyűjteményben lévő összes elem számát. Csak olvasható int.

**Visszatérési érték:**
int