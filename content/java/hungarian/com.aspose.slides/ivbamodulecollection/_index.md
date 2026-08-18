---
title: IVbaModuleCollection
second_title: Aspose.Slides Java API referencia
description: Egy VBA projekthez tartozó modulok gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/ivbamodulecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Egy VBA projekthez tartozó modulok gyűjteményét reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Új üres modult ad a VBA projekthez. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Eltávolítja a gyűjteményből egy adott objektum első előfordulását. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

A megadott indexű elemet adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

Új üres modult ad a VBA projekthez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A modul neve |

**Visszatérési érték:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Hozzáadott modul.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

Eltávolítja a gyűjteményből egy adott objektum első előfordulását.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Az eltávolítandó modul a gyűjteményből. |