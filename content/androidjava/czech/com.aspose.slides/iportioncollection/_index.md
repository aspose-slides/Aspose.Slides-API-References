---
title: IPortionCollection
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Zastupuje kolekci částí.
type: docs
url: /cs/com.aspose.slides/iportioncollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Zastupuje kolekci částí.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getCount()](#getCount--) | Získá počet skutečně obsažených prvků v kolekci. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Přidá Portion na konec kolekce. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Určuje index konkrétní části v kolekci. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Vloží Portion do kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Získá prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet skutečně obsažených prvků v kolekci. Int pouze pro čtení.

**Návratová hodnota:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Přidá Portion na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, který má být přidán na konec kolekce. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Určuje index konkrétní části v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Část, která se má v kolekci vyhledat. |

**Návratová hodnota:**
int - Index položky, pokud je v kolekci nalezena; jinak -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Vloží Portion do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index, na který má být Portion vložena. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, která má být vložena. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny prvky z kolekce.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který se má vyhledat v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Návratová hodnota:**
boolean - true, pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objekt, který má být odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Návratová hodnota:**
boolean - true, pokud byla položka úspěšně odstraněna z [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false. Tato metoda také vrací false, pokud položka není nalezena v původním [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní prvek na zadaném indexu kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index prvku, který má být odstraněn. |