---
title: AddFallBackFonts()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge un nuovo font(i) all'elenco dei font di fallback.
type: docs
weight: 40
url: /it/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) metodo


Aggiunge un nuovo font(i) all'elenco dei font di fallback.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nome o nomi del font (separati da virgola) per il fallback |
## Osservazioni



```cpp
//Crea una nuova istanza di FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Aggiunge un secondo font alla regola
newRule->AddFallBackFonts(u"MS Gothic");
//Aggiunge un terzo e quarto font alla regola
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metodo


Aggiunge nuovi font all'elenco dei font di fallback.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nome o nomi del font (separati da virgola) per il fallback |
## Osservazioni



```cpp
//Crea una nuova istanza di FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Aggiunge altri tre font alla regola
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)