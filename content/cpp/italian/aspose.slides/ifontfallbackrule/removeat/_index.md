---
title: RemoveAt()
second_title: Riferimento API Aspose.Slides per C++
description: Rimuove il font FallBack all'indice specificato della lista.
type: docs
weight: 92
url: /it/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) metodo

Rimuove il font FallBack all'indice specificato dell'elenco.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero del font da rimuovere. |
## Osservazioni

```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Rimozione di Tahoma dalla lista
newRule->RemoveAt(2);
```

## Vedi anche

* Classe [IFontFallBackRule](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)