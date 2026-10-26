---
title: IndexOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'indice della regola specificata nella raccolta.
type: docs
weight: 157
url: /it/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) metodo


Restituisce l'indice della regola specificata nella raccolta.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nome del font da trovare. |

### Valore di ritorno

Indice di un font o -1 se il font non è presente nell'elenco.
## Osservazioni



```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Ottieni l'indice di Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)