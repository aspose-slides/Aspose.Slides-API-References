---
title: RemoveAt()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove il font FallBack all'indice specificato dell'elenco.
type: docs
weight: 131
url: /it/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) metodo

Rimuove il font FallBack all'indice specificato dell'elenco.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero del font da rimuovere. |
## Osservazioni

```cpp
// Crea una regola che contiene un elenco di font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Rimuove Tahoma dall'elenco.
newRule->RemoveAt(2);
```

## Vedi anche

* Classe [FontFallBackRule](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)