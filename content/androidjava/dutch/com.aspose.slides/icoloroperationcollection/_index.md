---
title: IColorOperationCollection
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een verzameling van kleurtransformatie-operaties voor.
type: docs
url: /nl/com.aspose.slides/icoloroperationcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Stelt een verzameling van kleurtransformatie-operaties voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Geeft de bewerking op de opgegeven index terug of stelt deze in. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Geeft de bewerking op de opgegeven index terug of stelt deze in. |
| [add(int operation, float parameter)](#add-int-float-) | Voegt een nieuwe bewerking toe aan het einde van de collectie. |
| [add(int operation)](#add-int-) | Voegt een nieuwe bewerking toe aan het einde van de collectie. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Voegt de nieuwe bewerking in een verzameling in. |
| [insert(int position, int operation)](#insert-int-int-) | Voegt de nieuwe bewerking in een verzameling in. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de kleurbewerking uit een verzameling. |
| [clear()](#clear--) | Verwijdert alle kleurbewerkingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Geeft de bewerking op de opgegeven index terug of stelt deze in. Lezen/schrijven [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Geeft de bewerking op de opgegeven index terug of stelt deze in. Lezen/schrijven [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Voegt een nieuwe bewerking toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operation | int | Beweringstype. |
| parameter | float | Parameter van de bewerking. |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Toegevoegde bewerking.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Voegt een nieuwe bewerking toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operation | int | Beweringstype. |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Toegevoegde bewerking.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Voegt de nieuwe bewerking toe aan een verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | int | De index waarop de bewerking wordt ingevoegd. |
| operation | int | Beweringstype. |
| parameter | float | Parameter van de bewerking. |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ingevoegde bewerking.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Voegt de nieuwe bewerking toe aan een verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | int | De index waarop de bewerking wordt ingevoegd. |
| operation | int | Beweringstype. |

**Retour:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ingevoegde bewerking.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert de kleurbewerking uit een verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een te verwijderen kleurbewerking. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle kleurbewerkingen.