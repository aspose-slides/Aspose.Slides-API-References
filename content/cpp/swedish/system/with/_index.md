---
title: With()
second_title: Aspose.Slides för C++ API-referens
description: Klonar referensposten och tillämpar initialiseringsfunktor på den.
type: docs
weight: 2614
url: /sv/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) function

Klonar referensposten och tillämpar initialiseringsfunktor på den.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Posttyp att klona. |
| A | Typ av initialiseringsfunktor. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Delad pekare till objektet som ska klonas och initieras. |
| initializer | const A\& | Initialiseringsfunktor som appliceras på klonad post. |

### Return Value

Delad pekare till den klonade posten.

## System::With(const T\&, const A\&) function

Kopierar structposten och tillämpar initialiseringsfunktor på den.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Posttyp att kopiera. |
| A | Typ av initialiseringsfunktor. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | const T\& | Post att kopiera och initiera. |
| initializer | const A\& | Initialiseringsfunktor som appliceras på den kopierade posten. |

### Return Value

Kopierad post.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)