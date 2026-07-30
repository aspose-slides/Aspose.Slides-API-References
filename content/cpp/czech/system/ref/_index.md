---
title: Ref()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytváří odkaz na objekt DynamicWeakPtr. Používá se překladačem při předávání argumentů funkce jako reference.
type: docs
weight: 2458
url: /cs/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) function

Vytváří odkaz na objekt [DynamicWeakPtr](../dynamicweakptr/). Používá se překladačem při předávání argumentů funkce jako reference.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ ukazované položky. |
| trunkMode | Režim samotného chytrého ukazatele. |
| weakLeafs | Indexy šablonových argumentů, pro které musí být volána metoda SetTemplateWeakPtr. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Inteligentní ukazatel, na který se má vytvořit odkaz. |

### Návratová hodnota

Reference na chytrý ukazatel.

## System::Ref(T\&) function

Pomocná funkce pro získání odkazů na objekty. Používá se k zajištění, že [System::DynamicWeakPtr](../dynamicweakptr/) aktualizuje odkazovaný objekt po přiřazeních.

```cpp
template<typename T> T & System::Ref(T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, na který se má vytvořit odkaz. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T\& | Hodnota, na kterou se má vytvořit odkaz. |

### Návratová hodnota

Odkaz na hodnotu předanou této funkci.

## Viz také

* Třída [DynamicWeakPtr](../dynamicweakptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)