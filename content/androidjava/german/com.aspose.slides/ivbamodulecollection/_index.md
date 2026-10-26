---
title: IVbaModuleCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung von VBA-Projektmodulen dar.
type: docs
url: /de/com.aspose.slides/ivbamodulecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Stellt eine Sammlung von VBA-Projektmodulen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Fügt dem VBA-Projekt ein neues leeres Modul hinzu. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

Ruft das Element am angegebenen Index ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

Fügt dem VBA-Projekt ein neues leeres Modul hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des Moduls |

**Rückgabewert:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Hinzugefügtes Modul.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Das zu entfernende Modul aus der Sammlung. |