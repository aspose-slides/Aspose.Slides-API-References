---
title: IPointCollection
second_title: Aspose.Slides for Android Java API hivatkozás
description: Egy részek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ipointcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

Egy részek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a pontok számát a gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy pontot a megadott indexnél. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja a pontok számát a gyűjteményben. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```

Visszaad egy pontot a megadott indexnél.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatér:**
[IPoint](../../com.aspose.slides/ipoint) - A [IPoint](../../com.aspose.slides/ipoint) objektum.