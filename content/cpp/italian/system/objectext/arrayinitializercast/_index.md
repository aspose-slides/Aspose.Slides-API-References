---
title: ArrayInitializerCast()
second_title: Riferimento API Aspose.Slides per C++
description: Converte i valori fondamentali dell'array (che C# fa implicitamente ma C++ apparentemente non lo fa).
type: docs
weight: 209
url: /it/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) metodo

Converte i valori fondamentali dell'array (che C# fa implicitamente ma C++ apparentemente non lo fa).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| To | Tipo di destinazione. |
| From | Tipi di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | From ... | Valori da convertire e inserire nell'array di destinazione. |

### Valore restituito

[Array](../../array/) contenente copie convertite di tutti gli argomenti nello stesso ordine.

## Vedi anche

* Classe [ObjectExt](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)