---
title: Get()
second_title: Aspose.Slides für C++ API-Referenz
description: Funktion, um das N-te Element des angegebenen Tupels zu erhalten. Überladung für Basisobjekt.
type: docs
weight: 2406
url: /de/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) Funktion

Funktion zum Abrufen des N-ten Elements des angegebenen Tupels. Überladung für Basisobjekt.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| N | Elementindex. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | Objekt zu inspizieren. |

### Rückgabewert

Wert des N-ten Tupel-Elements, gecastet zu object.

## System::Get(const T\&) Funktion

Funktion zum Abrufen des N-ten Elements des angegebenen Tupels. Überladung für Objekte mit Deconstruct-Methode.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| N | Elementindex. |
| T | Typ des geprüften Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| object | const T\& | Objekt zu inspizieren. |

### Rückgabewert

Wert des N-ten Tupel-Elements.

## System::Get(const SharedPtr\<T\>\&) Funktion

Funktion zum Abrufen des N-ten Elements des angegebenen Tupels. Überladung für Shared-Pointer.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| N | Elementindex. |
| T | Typ des geprüften Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | Objekt zu inspizieren. |

### Rückgabewert

Wert des N-ten Tupel-Elements.

## System::Get(T\&, const Index\&) Funktion

Implementierung für collection[index]-Ausdrücke.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Sammlungstyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| collection | T\& | Sammlungsobjekt. |
| index | const [Index](../index/)\& | Elementindex vom Typ [System.Index](../index/). |

### Rückgabewert

Sammlungs-Element am berechneten Offset.

## System::Get(T\&, const Range\&) Funktion

Gibt einen Ausschnitt der angegebenen Sammlung zurück, definiert durch den bereitgestellten Bereich.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| collection | T\& | Die zu teilende Sammlung. |
| range | const [Range](../range/)\& | Der Bereich, der die Grenzen des Ausschnitts definiert. |

### Rückgabewert

Eine Ansicht oder ein Ausschnitt der Sammlung vom berechneten Start-Offset und der Länge.

## System::Get(const ValueTuple\<Args...\>\&) Funktion

Ermittelt das N-te Element des ValueTuple.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| N | Elementindex. |
| Args | Tupel-Elemente. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | Tupel, aus dem das Element entnommen wird. |

### Rückgabewert

Wert des N-ten Tupel-Elements.

## Siehe auch

* Typedef [SharedPtr](../sharedptr/)
* Klasse [Object](../object/)
* Klasse [Index](../index/)
* Klasse [Range](../range/)
* Klasse [ValueTuple](../valuetuple/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)