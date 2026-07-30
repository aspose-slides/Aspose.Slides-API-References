---
title: Remove()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove la prima occorrenza di un font FallBack specifico dall'elenco.
type: docs
weight: 79
url: /it/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) metodo


Rimuove la prima occorrenza di un font FallBack specifico dall'elenco.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Il nome del font da rimuovere dall'elenco. |
## Osservazioni



```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Rimozione di Tahoma dall'elenco
newRule->Remove(u"Tahoma");
```


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)