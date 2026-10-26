---
title: SensitivityLabelCollection
second_title: Aspose.Slides for Android Java API referencia
description: A dokumentumra alkalmazott érzékenységi címkék gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/sensitivitylabelcollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

A dokumentumra alkalmazott érzékenységi címkék gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Az index szerinti érzékenységi címkét adja vissza. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Az érzékenységi címkét a gyűjtemény végéhez adja hozzá. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Egy SensitivityLabel objektumot ad a gyűjteményhez. |
| [removeAt(int index)](#removeAt-int-) | Az adott indexnél lévő érzékenységi címkét eltávolítja. |
| [clear()](#clear--) | A gyűjtemény összes elemét eltávolítja. |
| [iterator()](#iterator--) | Egy enumerátort ad vissza, amely a gyűjteményen iterál. |
| [getCount()](#getCount--) | Visszaadja a gyűjtemény elemeinek számát. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | A gyűjtemény összes elemét a megadott tömbbe másolja. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

Az index szerinti érzékenységi címkét adja vissza.

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

Az érzékenységi címkét a gyűjtemény végéhez adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | java.lang.String | Az érzékenységi címke azonosítója. |
| siteId | java.util.UUID | Az Azure Active Directory (Azure AD) helyazonosítója. |
| isEnabled | boolean | Jelző, amely azt jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| methodType | int | Az érzékenységi címke hozzárendelési módszere. |

**Visszatérési érték:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

Egy SensitivityLabel objektumot ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Az a SensitivityLabel objektum, amelyet a gyűjtemény végére adunk hozzá. |

**Visszatérési érték:**
int – Az az index, amelynél a SensitivityLabel hozzá lett adva.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Az adott indexnél lévő érzékenységi címkét eltávolítja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az érzékenységi címke indexe, amelyet törölni kell. |
### clear() {#clear--}
```
public final void clear()
```

A gyűjtemény összes elemét eltávolítja.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

Egy enumerátort ad vissza, amely a gyűjteményen iterál.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> – egy System.Collections.Generic.IEnumerator1, amely a gyűjteményen való iteráláshoz használható.
### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja a gyűjtemény elemeinek számát. Csak olvasható int .

**Visszatérési érték:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

A gyűjtemény összes elemét a megadott tömbbe másolja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |