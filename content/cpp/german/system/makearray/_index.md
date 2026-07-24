---
title: MakeArray()
second_title: Aspose.Slides für C++ API Referenz
description: Eine Fabrikfunktion, die ein neues Array-Objekt erzeugt, es mit den Elementen aus der angegebenen Initialisierungsliste füllt und einen Smart-Pointer zurückgibt, der auf das Array-Objekt zeigt.
type: docs
weight: 2029
url: /de/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) Funktion


Eine Fabrikfunktion, die ein neues [Array](../array/)-Objekt erzeugt, es mit den Elementen aus der angegebenen Initialisierungsliste füllt und einen Smart-Pointer zurückgibt, der auf das [Array](../array/)-Objekt zeigt.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente des [Array](../array/)-Objekts, das die Funktion konstruiert |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Die Initialisierungsliste, die die Elemente enthält, mit denen das Array gefüllt wird |

### Rückgabewert

Ein Smart-Pointer, der auf das konstruierte [Array](../array/)-Objekt zeigt

## System::MakeArray(Args\&&...) Funktion


Eine Fabrikfunktion, die ein neues [Array](../array/)-Objekt erzeugt und die angegebenen Argumente an dessen Konstruktor übergibt.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente des [Array](../array/)-Objekts, das die Funktion konstruiert |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | Args\&&... | Die Argumente, die an den Konstruktor des [Array](../array/)-Objekts übergeben werden, das konstruiert wird |

### Rückgabewert

Ein Smart-Pointer, der auf das konstruierte [Array](../array/)-Objekt zeigt

## System::MakeArray(Integral, Args\&&...) Funktion


Eine Fabrikfunktion, die ein neues [Array](../array/)-Objekt erzeugt und die angegebenen Argumente an dessen Konstruktor übergibt.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente des [Array](../array/)-Objekts, das die Funktion konstruiert |
| Integral | Typ der Array-Größe. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | Integral | Größe des zu erstellenden Arrays. |
| args | Args\&&... | Die Argumente, die an den Konstruktor des [Array](../array/)-Objekts übergeben werden, das konstruiert wird |

### Rückgabewert

Ein Smart-Pointer, der auf das konstruierte [Array](../array/)-Objekt zeigt

## Siehe auch

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)