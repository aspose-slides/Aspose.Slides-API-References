---
title: RemoveScriptFont()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove l'impostazione del carattere associata a un tag di script specifico dalla collezione di caratteri del tema.
type: docs
weight: 118
url: /it/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) metodo

Rimuove l'impostazione del carattere associata a un tag di script specifico dalla collezione di caratteri del tema.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Il codice script BCP-47 la cui impostazione del carattere dovrebbe essere rimossa. |

## Osservazioni

Questo esempio dimostra come rimuovere la mappatura del carattere per lo script ebraico:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)