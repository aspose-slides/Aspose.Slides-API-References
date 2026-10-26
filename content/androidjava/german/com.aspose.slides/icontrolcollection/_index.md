---
title: IControlCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Eine Sammlung von ActiveX-Steuerelementen.
type: docs
url: /de/com.aspose.slides/icontrolcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Eine Sammlung von ActiveX-Steuerelementen.
## Methoden

| Method | Beschreibung |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Entfernt ein ActiveX-Steuerelement aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein ActiveX-Steuerelement, das an einer angegebenen Position gespeichert ist, aus der Sammlung. |
| [clear()](#clear--) | Entfernt alle Steuerelemente aus der Sammlung. |
| [get_Item(int index)](#get-Item-int-) | Gibt ein Steuerelement an der angegebenen Position zurück. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Erstellt ein neues Steuerelement und fügt es der Sammlung hinzu. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Entfernt ein ActiveX-Steuerelement aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Ein zu entfernendes Steuerelement. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt ein ActiveX-Steuerelement, das an einer angegebenen Position gespeichert ist, aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines zu entfernenden Steuerelements. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Steuerelemente aus der Sammlung.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Gibt ein Steuerelement an der angegebenen Position zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Steuerelements. |

**Rückgabe:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Erstellt ein neues Steuerelement und fügt es der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| controlType | int | Typ eines hinzuzufügenden Steuerelements. |
| x | float | Die X-Koordinate für die linke Seite des Rahmens der Form. |
| y | float | Die Y-Koordinate für die obere Seite des Rahmens der Form. |
| width | float | Die Breite des Rahmens der Form. |
| height | float | Die Höhe des Rahmens der Form. |

**Rückgabe:**
[IControl](../../com.aspose.slides/icontrol) - Erstelltes Steuerelement [IControl](../../com.aspose.slides/icontrol).