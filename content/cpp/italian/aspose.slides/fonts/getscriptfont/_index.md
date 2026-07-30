---
title: GetScriptFont()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il nome del carattere associato a un tag di script specifico dal tema della presentazione.
type: docs
weight: 92
url: /it/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) metodo

Restituisce il nome del carattere associato a un tag di script specifico dal tema della presentazione.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Il codice script BCP-47 (ad es., "Latn", "Cyrl", "Jpan") usato per identificare un sistema di scrittura. |

### Valore di ritorno

Il nome del carattere usato per lo script specificato, o **null** se lo script non è definito.

## Osservazioni

Questo esempio dimostra come recuperare il carattere assegnato allo script cirillico nel tema della presentazione. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)