---
title: Cast()
second_title: Aspose.Slides for C++ API Referencia
description: Átalakítja a mutatót a saját típusára.
type: docs
weight: 287
url: /hu/system/smartptr/cast/
---
## SmartPtr::Cast() const metódus

Átalakítja a mutatót a saját típusára.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Y | A mutatott objektum céltípusa. |
| Check | Jelzők, amelyek kivételt dobnak, ha nincs elérhető átkonvertálás. |

### Visszatérési érték

A módosított típusú mutató, amely mindig megosztott módban van.

## SmartPtr::Cast() const metódus

Átalakítja a mutatót az alaptípusra static_cast használatával.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Y | A mutatott objektum céltípusa. |
| Check | Jelzők, amelyek kivételt dobnak, ha nincs elérhető átkonvertálás. |

### Visszatérési érték

A módosított típusú mutató, amely mindig megosztott módban van.

## SmartPtr::Cast() const metódus

Átalakítja a mutatót a származtatott típusra dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Y | A mutatott objektum céltípusa. |
| Check | Jelzők, amelyek kivételt dobnak, ha nincs elérhető átkonvertálás. |

### Visszatérési érték

A módosított típusú mutató, amely mindig megosztott módban van. InvalidCastException kivételt dob, ha a konverzió nem érhető el.

## SmartPtr::Cast() const metódus

Átalakítja a mutatót a származtatott típusra dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Y | A mutatott objektum céltípusa. |
| Check | Jelzők, amelyek kivételt dobnak, ha nincs elérhető átkonvertálás. |

### Visszatérési érték

A módosított típusú mutató, amely mindig megosztott módban van. nullptr értéket ad vissza, ha a konverzió nem érhető el.

## Lásd még

* Osztály [SmartPtr](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)