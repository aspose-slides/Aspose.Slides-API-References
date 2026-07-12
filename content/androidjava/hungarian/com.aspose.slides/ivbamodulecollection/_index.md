---
title: IVbaModuleCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: A VBA projekt moduljainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ivbamodulecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Represents a collection of a VBA Project modules.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexnél lévő elemet adja vissza. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Új üres modult ad a VBA projekthez. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Az adott objektum első előfordulását távolítja el a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


A megadott indexnél lévő elemet adja vissza.

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


Az adott objektum első előfordulását távolítja el a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | A gyűjteményből eltávolítandó modul. |