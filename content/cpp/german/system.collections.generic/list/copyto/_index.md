---
title: CopyTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Kopiert Listenelemente in vorhandene Array-Elemente.
type: docs
weight: 209
url: /de/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) Methode

Kopiert Listenelemente in vorhandene Array-Elemente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Ziel-Array. |
| arrayIndex | int | Startindex des Ziel-Arrays. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) Methode

Kopiert alle Elemente in vorhandene Array-Elemente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) zum Kopieren von Elementen in. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) Methode

Kopiert Elemente beginnend beim angegebenen Index in vorhandene Array-Elemente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Ein 0-basierter Index des Elements in der Liste, die durch das aktuelle Objekt repräsentiert wird, von dem aus das Kopieren beginnt |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) zum Kopieren von Elementen in. |
| arrayIndex | int | Startposition im Ziel-Array. |
| count | int | Anzahl der zu kopierenden Elemente. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [List](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)