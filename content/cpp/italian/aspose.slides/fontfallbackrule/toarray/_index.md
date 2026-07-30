---
title: ToArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea e restituisce un array con tutti i font di fallback per questa regola.
type: docs
weight: 144
url: /it/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() metodo

Crea e restituisce un array con tutti i font di fallback per questa regola.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Valore di ritorno

Array di [System::String](../../../system/string/)
## Note

```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Ottieni tutti i nomi dei font come array.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) metodo

Crea e restituisce un array con tutti i font di fallback dall'intervallo specificato nella lista.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **int32_t** | Un indice del primo font da aggiungere. |
| count | **int32_t** | Il numero di font da aggiungere. |

### Valore di ritorno

Array di [System::String](../../../system/string/)
## Note

```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Ottieni gli ultimi due nomi dei font come array.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)