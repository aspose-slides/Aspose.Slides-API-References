---
title: MakeObject()
second_title: Aspose.Slides C++ API referencia
description: Objektumot hoz létre a heapen, és visszaad egy megosztott mutatót rá.
type: docs
weight: 2887
url: /hu/system/makeobject/
---
## System::MakeObject(Args\&&...) függvény


Objektumot hoz létre a heapen, és visszaad egy megosztott mutatót rá.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az osztály, amelyet példányosítani kell. |
| Args | A konstruktor argumentumainak típusai. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | Args\&&... | Konstruktor argumentumok. |

### Visszatérési érték

[SmartPtr](../smartptr/) az újonnan létrehozott objektumra, mindig megosztott módban.

## System::MakeObject(Args\&&...) függvény


Objektumot hoz létre a heapen, és visszaad egy megosztott mutatót rá.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [SmartPtr](../smartptr/) az osztályra, amelyet példányosítani kell. |
| Args | A konstruktor argumentumainak típusai. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | Args\&&... | Konstruktor argumentumok. |

### Visszatérési érték

[SmartPtr](../smartptr/) az újonnan létrehozott objektumra, mindig megosztott módban.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Struktúra [IsSmartPtr](../issmartptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)