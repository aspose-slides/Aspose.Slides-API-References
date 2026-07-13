---
title: IVbaModuleCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van VBA-projectmodules voor.
type: docs
url: /nl/com.aspose.slides/ivbamodulecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Stelt een collectie van VBA-projectmodules voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Voegt een nieuwe lege module toe aan het VBA-project. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Verwijdert de eerste voorkoming van een specifiek object uit de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

Voegt een nieuwe lege module toe aan het VBA-project.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de module |

**Retour:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Toegevoegde module.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

Verwijdert de eerste voorkoming van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | De module die uit de collectie moet worden verwijderd. |