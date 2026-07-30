---
title: RemoveScriptFont()
second_title: Aspose.Slides per C++ API Reference
description: Rimuove l'impostazione del font associata a un tag script specifico dalla collezione di font del tema.
type: docs
weight: 118
url: /it/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) metodo


Rimuove l’impostazione del font associata a un tag script specifico dalla collezione di font del tema.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Il codice script BCP-47 la cui impostazione del font deve essere rimossa. |
## Osservazioni



Questo esempio dimostra come rimuovere la mappatura del font per lo script ebraico: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IFonts](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)