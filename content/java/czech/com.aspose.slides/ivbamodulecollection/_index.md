---
title: IVbaModuleCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci modulů VBA projektu.
type: docs
url: /cs/com.aspose.slides/ivbamodulecollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Reprezentuje kolekci modulů VBA projektu.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na určeném indexu. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Přidá nový prázdný modul do VBA projektu. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Odstraní první výskyt konkrétního objektu z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

Získá prvek na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

Přidá nový prázdný modul do VBA projektu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název modulu |

**Návratová hodnota:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Přidaný modul.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

Odstraní první výskyt konkrétního objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Modul, který se má odstranit z kolekce. |
