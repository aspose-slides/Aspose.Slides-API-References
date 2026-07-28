---
title: ForEach()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Wykonuje operację foreach na IEnumerable, w której iteracje mogą być uruchamiane równolegle.
type: docs
weight: 1
url: /pl/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) metoda

Wykonuje operację foreach na IEnumerable, w której iteracje mogą być uruchamiane równolegle.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSource | Typ danych w źródle. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Źródło danych typu enumerable. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Obiekt konfiguracyjny zachowania tej operacji. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Delegat wywoływany raz na iterację. |

### Wartość zwracana

Struktura [ParallelLoopResult](../../parallelloopresult/) zawierająca informacje o tym, jaka część pętli została zakończona.

## Uwagi

Ta metoda dzieli źródłowy enumerable i równocześnie wykonuje delegata body na wielu wątkach.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) metoda

Wykonuje operację foreach na IEnumerable, w której iteracje mogą być uruchamiane równolegle.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSource | Typ danych w źródle. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Źródło danych typu enumerable. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Delegat wywoływany raz na iterację. |

### Wartość zwracana

Struktura [ParallelLoopResult](../../parallelloopresult/) zawierająca informacje o tym, jaka część pętli została zakończona.

## Uwagi

Używa domyślnego [ParallelOptions](../../paralleloptions/) z nieograniczoną równoległością i bez anulowania.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Klasa [ParallelLoopResult](../../parallelloopresult/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasa [ParallelOptions](../../paralleloptions/)
* Klasa [Parallel](../)
* Przestrzeń nazw [System::Threading::Tasks](../../)
* Biblioteka [Aspose.Slides](../../../)