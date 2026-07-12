---
title: IControlCollection
second_title: Aspose.Slides Androidra a Java API hivatkozással
description: ActiveX vezérlők gyűjteménye.
type: docs
url: /hu/com.aspose.slides/icontrolcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Az ActiveX vezérlők gyűjteménye.
## Módszerek

| Method | Description |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Eltávolít egy ActiveX vezérlőt a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy a megadott pozícióban tárolt ActiveX vezérlőt a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes vezérlőt a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy vezérlőt a megadott pozícióban. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Létrehoz és hozzáad egy új vezérlőt a gyűjteményhez. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Eltávolít egy ActiveX vezérlőt a gyűjteményből.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Eltávolítandó vezérlő. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy a megadott pozícióban tárolt ActiveX vezérlőt a gyűjteményből.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az eltávolítandó vezérlő indexe. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes vezérlőt a gyűjteményből.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Visszaad egy vezérlőt a megadott pozícióban.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A vezérlő indexe. |

**Visszatérési érték:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Létrehozza és hozzáadja az új vezérlőt a gyűjteményhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| controlType | int | A hozzáadandó vezérlő típusa. |
| x | float | A forma keret bal oldalának X koordinátája. |
| y | float | A forma keret felső oldalának Y koordinátája. |
| width | float | A forma keret szélessége. |
| height | float | A forma keret magassága. |

**Visszatérési érték:**
[IControl](../../com.aspose.slides/icontrol) - Létrehozott vezérlő [IControl](../../com.aspose.slides/icontrol).