---
title: FontFallBackRule()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 66
url: /it/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) costruttore

Crea una nuova istanza.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **uint32_t** | Indice iniziale dell'intervallo unicode |
| endIndex | **uint32_t** | Indice finale dell'intervallo unicode |
| fontNames | [System::String](../../../system/string/) | Nome o nomi del font (separati da virgola) per FallBack |
## Osservazioni

```cpp
// Crea una nuova istanza di FantFallBackRule con un font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Crea una nuova istanza di FantFallBackRule con più font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) costruttore

Crea una nuova istanza.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | **uint32_t** | Indice iniziale dell'intervallo unicode |
| endIndex | **uint32_t** | Indice finale dell'intervallo unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nome o nomi del font (separati da virgola) per FallBack |
## Osservazioni

```cpp
// Crea una nuova istanza di FantFallBackRule con due font
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Crea una nuova istanza di FantFallBackRule con più font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)