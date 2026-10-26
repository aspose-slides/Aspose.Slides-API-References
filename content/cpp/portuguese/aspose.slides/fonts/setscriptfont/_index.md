---
title: SetScriptFont()
second_title: Referência da API Aspose.Slides para C++
description: Atribui um nome de fonte a uma tag de script específica, que define como o texto desse script será renderizado na apresentação.
type: docs
weight: 105
url: /pt/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) method


Atribui um nome de fonte a uma etiqueta de script específica, que define como o texto desse script será renderizado na apresentação.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | O código de script BCP-47 (por exemplo, \"Arab\", \"Hebr\", \"Hans\") que identifica o sistema de escrita. |
| fontName | [System::String](../../../system/string/) | O nome da fonte a ser atribuído ao script especificado. |
## Observações



Este exemplo mostra como definir a fonte para o script Árabe como \"Segoe UI\": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segue UI");
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)