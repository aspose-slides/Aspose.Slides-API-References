---
title: MakeObject()
second_title: Aspose.Slides dla C++ - odwołanie API
description: Tworzy obiekt na stercie i zwraca wskaźnik współdzielony do niego.
type: docs
weight: 2887
url: /pl/system/makeobject/
---
## System::MakeObject(Args\&&...) funkcja

Tworzy obiekt na stercie i zwraca wskaźnik współdzielony do niego.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Klasa do utworzenia. |
| Args | Typy argumentów konstruktora. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | Args\&&... | Argumenty konstruktora. |

### Wartość zwracana

[SmartPtr](../smartptr/) do nowo utworzonego obiektu, zawsze w trybie współdzielonym.

## System::MakeObject(Args\&&...) funkcja

Tworzy obiekt na stercie i zwraca wskaźnik współdzielony do niego.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [SmartPtr](../smartptr/) do klasy do utworzenia. |
| Args | Typy argumentów konstruktora. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | Args\&&... | Argumenty konstruktora. |

### Wartość zwracana

[SmartPtr](../smartptr/) do nowo utworzonego obiektu, zawsze w trybie współdzielonym.

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Struktura [IsSmartPtr](../issmartptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)