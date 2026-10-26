---
title: Clear()
second_title: Aspose.Slides für C++ API-Referenz
description: Nicht unterstützt, weil das vom aktuellen Objekt dargestellte Array schreibgeschützt ist.
type: docs
weight: 53
url: /de/system/array/clear/
---
## Array::Clear() Methode


Nicht unterstützt, weil das vom aktuellen Objekt dargestellte Array schreibgeschützt ist.

```cpp
virtual void System::Array<T>::Clear() override
```


## Array::Clear(const ArrayPtr\<Type\>\&, int, int) Methode


Ersetzt **count** Werte beginnend beim Index **startIndex** im angegebenen Array durch Standardwerte.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| Type | Typ der Elemente im Zielarray |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Zielarray |
| startIndex | int | [Index](../../index/) bei dem das Ersetzen der Elemente beginnen soll |
| count | int | Die Anzahl der zu ersetzenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Methode [Type](../../object/type/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)