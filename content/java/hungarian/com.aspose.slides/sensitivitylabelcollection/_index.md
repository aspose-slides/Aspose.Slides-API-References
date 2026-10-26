---
title: SensitivityLabelCollection
second_title: Aspose.Slides Java API referenciája
description: A dokumentumra alkalmazott érzékenységi címkék gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/sensitivitylabelcollection/
---
**Öröklődés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

A dokumentumra alkalmazott érzékenységi címkék gyűjteményét jelenti.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az érzékenységi címkét az index alapján. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Hozzáadja az érzékenységi címkét a gyűjtemény végéhez. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Hozzáad egy SensitivityLabel-t a gyűjteményhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az érzékenységi címkét a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [getCount()](#getCount--) | Visszaadja a gyűjtemény elemeinek számát. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |

### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

Visszaadja az érzékenységi címkét az index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Hozzáadja az érzékenységi címkét a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | java.lang.String | Az érzékenységi címke azonosítója. |
| siteId | java.util.UUID | Az Azure Active Directory (Azure AD) helyazonosító. |
| isEnabled | boolean | Jelző, amely azt mutatja, hogy az érzékenységi címke engedélyezve van-e. |
| methodType | int | Az érzékenységi címke hozzárendelési módja. |

**Visszatérési érték:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

Hozzáad egy SensitivityLabel-t a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Az SensitivityLabel objektum, amely a gyűjtemény végéhez lesz hozzáadva. |

**Visszatérési érték:**
int - Az az index, amelynél a SensitivityLabel hozzá lett adva.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja az érzékenységi címkét a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az érzékenységi címke indexe, amelyet törölni kell. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja a gyűjtemény összes elemét.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Egy  System.Collections.Generic.IEnumerator1  amelyet a gyűjtemény bejárásához lehet használni.
### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja a gyűjtemény elemeinek számát. Csak olvasható  int .

**Visszatérési érték:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |