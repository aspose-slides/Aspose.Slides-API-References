---
title: SetScriptFont()
second_title: Riferimento API di Aspose.Slides per C++
description: Assegna un nome di font a un tag script specifico, che definisce come il testo di quello script verrà visualizzato nella presentazione.
type: docs
weight: 105
url: /it/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) metodo

Assegna un nome di font a un tag di script specifico, che definisce come il testo di quello script verrà visualizzato nella presentazione.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Il codice script BCP-47 (ad es., "Arab", "Hebr", "Hans") che identifica il sistema di scrittura. |
| fontName | [System::String](../../../system/string/) | Il nome del font da assegnare allo script specificato. |

## Osservazioni

Questo esempio mostra come impostare il font per lo script arabo su "Segoe UI": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IFonts](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)