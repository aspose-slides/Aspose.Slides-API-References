---
title: ReadOnlySpan
second_title: Aspose.Slides pro C++ referenční příručku API
description: Určeno k použití ve třídě Span.
type: docs
weight: 1210
url: /cs/system/readonlyspan/
---
## ReadOnlySpan třída


Určeno k použití v rámci třídy [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu. Tato třída poskytuje typově bezpečný způsob práce s souvislými sekvencemi objektů jen pro čtení. Lze ji použít k zabalení polí, zásobníkových polí nebo surových ukazatelů při zachování kontroly hranic. [ReadOnlySpan](./) nevlastní paměť, na kterou ukazuje – je to jen pohled na existující paměť. |
## Metody

| Metoda | Popis |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Vytvoří rozmezí jen pro čtení z běžného rozmezí. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Převede pole na [ReadOnlySpan](./). |
## Poznámky


Representuje jen pro čtení souvislý region libovolné paměti.

## Viz také

* Namespace [System](../)
* Library [Aspose.Slides](../../)