---
title: MakeSharedPtr()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Převádí syrový ukazatel na chytrý ukazatel.
type: docs
weight: 2900
url: /cs/system/makesharedptr/
---
## System::MakeSharedPtr(X *) funkce

Převádí syrový ukazatel na chytrý ukazatel.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | Typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| p | X * | Syrový ukazatel na objekt. |

### Návratová hodnota

Sdílený chytrý ukazatel na objekt.

## System::MakeSharedPtr(const X *) funkce

Převádí syrový ukazatel na chytrý ukazatel. Přetížení pro ukazatele na const. Užitečné např. při použití proměnné 'this' v metodách C# přeložených jako const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | Typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| p | const X * | Syrový ukazatel na objekt. |

### Návratová hodnota

Sdílený chytrý ukazatel na objekt.

## Viz také

* Třída [SmartPtr](../smartptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)