---
title: GetScriptFont()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene il nome del font associato a un tag script specifico dal tema della presentazione.
type: docs
weight: 92
url: /it/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) method


Ottiene il nome del font associato a un tag di script specifico dal tema della presentazione.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Il codice script BCP-47 (ad es., "Latn", "Cyrl", "Jpan") usato per identificare un sistema di scrittura. |

### Valore di ritorno

Il nome del font usato per lo script specificato, oppure **null** se lo script non è definito.
## Osservazioni



Questo esempio dimostra come recuperare il font assegnato allo script cirillico nel tema della presentazione. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IFonts](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)