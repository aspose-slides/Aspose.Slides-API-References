---
title: ToArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea e restituisce un array con tutti i font FallBack per questa regola.
type: docs
weight: 105
url: /it/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() metodo

Crea e restituisce un array con tutti i font FallBack per questa regola.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### Valore di ritorno

Array di [System::String](../../../system/string/)
## Osservazioni

```cpp
// Crea una regola che contiene una lista di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Ottieni tutti i nomi dei font come array
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) metodo

Crea e restituisce un array con tutti i font FallBack dall'intervallo specificato nella lista.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice del primo font da aggiungere. |
| count | **int32_t** | Un numero di font da aggiungere. |

### Valore di ritorno

Array di [System::String](../../../system/string/)
## Osservazioni

```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Ottieni gli ultimi due nomi dei font come array
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)