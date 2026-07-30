---
title: With()
second_title: Aspose.Slides pro C++ API Reference
description: Klonuje referenční záznam a použije na něj inicializační funktor.
type: docs
weight: 2614
url: /cs/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) funkce


Klonuje referenční záznam a použije na něj inicializační funktor.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ záznamu, který se má klonovat. |
| A | Typ inicializačního funktoru. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Sdílený ukazatel na objekt, který se má klonovat a inicializovat. |
| initializer | const A\& | Inicializační funktor, který se použije na klon záznamu. |

### Návratová hodnota

Sdílený ukazatel na klonovaný záznam.

## System::With(const T\&, const A\&) funkce


Zkopíruje strukturovaný záznam a použije na něj inicializační funktor.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ záznamu, který se má kopírovat. |
| A | Typ inicializačního funktoru. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| record | const T\& | Záznam, který se má zkopírovat a inicializovat. |
| initializer | const A\& | Inicializační funktor, který se použije na kopii záznamu. |

### Návratová hodnota

Zkopírovaný záznam.

## Viz také

* Definice typu [SharedPtr](../sharedptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)