---
title: ITabCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie tabbladen voor.
type: docs
url: /nl/com.aspose.slides/itabcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Stelt een collectie Tab-objecten voor.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op de opgegeven index. |
| [add(double position, int align)](#add-double-int-) | Voegt een Tab toe aan de collectie. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Voegt een Tab toe aan de collectie. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Haalt het element op de opgegeven index. Alleen-lezen [ITab](../../com.aspose.slides/itab).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Voegt een Tab toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | double | Tab-positie. |
| align | int | Tab-uitlijning. |

**Retour:**
[ITab](../../com.aspose.slides/itab) - Toegevoegde tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Voegt een Tab toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Het Tab-object dat aan het einde van de collectie moet worden toegevoegd. |

**Retour:**
int - De index waarop de tab is toegevoegd.
### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen uit de collectie.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De index (beginnend bij nul) van het te verwijderen element. |