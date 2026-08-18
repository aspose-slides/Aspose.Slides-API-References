---
title: ISensitivityLabelCollection
second_title: Aspose.Slides Java API referencia
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
| [get_Item(int index)](#get-Item-int-) | Returns the sensitivity label by index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Adds the sensitivity label at the end of the collection. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Adds a SensitivityLabel to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the sensitivity label at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Gets the number of all elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


Returns the sensitivity label by index. Csak olvasható [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

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


A gyűjtemény végére adja hozzá az érzékenységi címkét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | java.lang.String | Az érzékenységi címke azonosítója. |
| siteId | java.util.UUID | Az Azure Active Directory (Azure AD) webhelyazonosítója. |
| isEnabled | boolean | A jelző azt jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| methodType | int | Az érzékenységi címke hozzárendelési módja. |

**Visszatérési érték:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


Egy SensitivityLabel objektumot ad a gyűjmentényhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | A SensitivityLabel objektum, amely a gyűjtemény végére kerül. |

**Visszatérési érték:**
int - Az az index, amelyhez a SensitivityLabel hozzá lett adva.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a megadott indexű érzékenységi címkét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az érzékenységi címke indexe, amelyet törölni kell. |

### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja a gyűjtemény összes elemét.

### getCount() {#getCount--}
```
public abstract int getCount()
```


A gyűjtemény összes elemének számát adja vissza. Csak olvasható  int .

**Visszatérési érték:**
int