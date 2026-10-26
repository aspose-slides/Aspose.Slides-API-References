---
title: Cast()
second_title: Aspose.Slides pro C++ referenci API
description: Přetypuje ukazatel na jeho vlastní typ.
type: docs
weight: 287
url: /cs/system/smartptr/cast/
---
## SmartPtr::Cast() const metoda

Přetypuje ukazatel na jeho vlastní typ.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Y | Cílový typ ukazovaného objektu. |
| Check | Příznaky pro vyvolání výjimky, pokud převod není k dispozici. |

### Návratová hodnota

Ukazatel změněného typu, který je vždy ve sdíleném režimu.

## SmartPtr::Cast() const metoda

Přetypuje ukazatel na základní typ pomocí static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Y | Cílový typ ukazovaného objektu. |
| Check | Příznaky pro vyvolání výjimky, pokud převod není k dispozici. |

### Návratová hodnota

Ukazatel změněného typu, který je vždy ve sdíleném režimu.

## SmartPtr::Cast() const metoda

Přetypuje ukazatel na odvozený typ pomocí dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Y | Cílový typ ukazovaného objektu. |
| Check | Příznaky pro vyvolání výjimky, pokud převod není k dispozici. |

### Návratová hodnota

Ukazatel změněného typu, který je vždy ve sdíleném režimu. Vyvolá InvalidCastException, pokud není konverze k dispozici.

## SmartPtr::Cast() const metoda

Přetypuje ukazatel na odvozený typ pomocí dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Y | Cílový typ ukazovaného objektu. |
| Check | Příznaky pro vyvolání výjimky, pokud převod není k dispozici. |

### Návratová hodnota

Ukazatel změněného typu, který je vždy ve sdíleném režimu. Vrátí nullptr, pokud není konverze k dispozici.

## Viz také

* Třída [SmartPtr](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)