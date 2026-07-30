---
title: Clear()
second_title: Aspose.Slides pro C++ API Reference
description: Není podporováno, protože pole reprezentované aktuálním objektem je jen pro čtení.
type: docs
weight: 53
url: /cs/system/array/clear/
---
## Array::Clear() metoda

Není podporováno, protože pole reprezentované aktuálním objektem je jen pro čtení.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) metoda

Nahradí **count** hodnot začínajících od indexu **startIndex** ve specifikovaném poli výchozími hodnotami.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Type | Typ prvků v cílovém poli |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Cílové pole |
| startIndex | int | [Index](../../index/), od kterého začít nahrazovat položky |
| count | int | Počet položek k nahrazení |

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Metoda [Type](../../object/type/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)