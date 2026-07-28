---
title: LastIndexOf()
second_title: Aspose.Slides C++ API-referencia
description: Keres a megadott objektumra, és visszaadja a teljes listában lévő utolsó előfordulás nullától indexelt helyét.
type: docs
weight: 469
url: /hu/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const method

Keres a megadott objektumra, és visszaadja a teljes listában szereplő utolsó előfordulás nullától indexelt helyét.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | const T\& | A listaban keresendő objektum |

### Visszatérési érték

Az elem utolsó előfordulásának nullától indexelt helye a teljes [List](../)-ben, ha megtalálható; egyébként -1.

## List::LastIndexOf(const T\&, int32_t) const method

Keres a megadott objektumra, és visszaadja a [List](../) elemeinek azon tartományában lévő utolsó előfordulás nullától indexelt helyét, amely az első elemről a megadott indexig terjed.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | const T\& | A listaban keresendő objektum |
| index | **int32_t** | A visszafelé keresés nullától indexelt kiindulási indexe. |

### Visszatérési érték

Az elem utolsó előfordulásának nullától indexelt helye a [List](../) elemeinek azon tartományában, amely az első elemtől az indexig terjed, ha megtalálható; egyébként -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const method

Keres a megadott objektumra, és visszaadja a [List](../) elemeinek azon tartományában lévő utolsó előfordulás nullától indexelt helyét, amely a megadott elemszámot tartalmazza és a megadott indexnél végződik.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | const T\& | A [List](../)-ben keresendő objektum |
| index | **int32_t** | A visszafelé keresés nullától indexelt kiindulási indexe. |
| count | **int32_t** | A keresendő szakasz elemeinek száma. |

### Visszatérési érték

Az elem utolsó előfordulásának nullától indexelt helye a [List](../) elemeinek azon tartományában, amely tartalmazza a count elemszámot és az indexnél végződik, ha megtalálható; egyébként -1.

## Lásd még

* Osztály [List](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)