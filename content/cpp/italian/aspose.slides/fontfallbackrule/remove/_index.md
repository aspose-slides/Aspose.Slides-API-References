---
title: Remove()
second_title: Riferimento API Aspose.Slides per C++
description: Rimuove la prima occorrenza di un font FallBack specifico dall'elenco.
type: docs
weight: 118
url: /it/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) metodo


Rimuove la prima occorrenza di un font FallBack specifico dall'elenco.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Il nome del font da rimuovere dall'elenco. |
## Osservazioni



```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Rimuove Tahoma dall'elenco.
newRule->Remove(u"Tahoma");
```


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)