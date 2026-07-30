---
title: AddFallBackFonts()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge nuovi font all'elenco dei font di fallback.
type: docs
weight: 79
url: /it/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) metodo

Aggiunge un nuovo font o più font all'elenco dei font di fallback.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nome o nomi del font (separati da virgola) per il fallback |
## Osservazioni



```cpp
// Crea una nuova istanza di FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Aggiungi un secondo font alla regola
newRule->AddFallBackFonts(u"MS Gothic");
//Aggiungi un terzo e un quarto font alla regola
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metodo

Aggiunge nuovi font all'elenco dei font di fallback.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nome o nomi del font (separati da virgola) per il fallback |
## Osservazioni



```cpp
//Crea una nuova istanza di FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Aggiungi altri tre font alla regola
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontFallBackRule](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)