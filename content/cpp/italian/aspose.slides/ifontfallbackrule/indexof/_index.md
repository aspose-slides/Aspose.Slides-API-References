---
title: IndexOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un indice della regola specificata nella raccolta.
type: docs
weight: 118
url: /it/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) method


Restituisce l'indice della regola specificata nella raccolta.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nome del font da trovare. |

### Valore restituito

Indice di un font o -1 se il font non è trovato nell'elenco.
## Osservazioni



```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Ottieni l'indice di Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)