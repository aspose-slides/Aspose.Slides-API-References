---
title: SetScriptFont()
second_title: Riferimento API di Aspose.Slides per C++
description: Assegna un nome di carattere a un tag script specifico, che definisce come il testo di quello script verrà renderizzato nella presentazione.
type: docs
weight: 105
url: /it/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) metodo

Assegna un nome di carattere a un tag script specifico, che definisce come il testo di quello script verrà visualizzato nella presentazione.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Il codice script BCP-47 (ad es., \"Arab\", \"Hebr\", \"Hans\") che identifica il sistema di scrittura. |
| fontName | [System::String](../../../system/string/) | Il nome del carattere da assegnare allo script specificato. |
## Osservazioni

Questo esempio mostra come impostare il carattere per lo script arabo su \"Segoe UI\": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segue UI");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)