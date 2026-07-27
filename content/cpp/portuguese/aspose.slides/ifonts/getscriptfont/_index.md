---
title: GetScriptFont()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o nome da fonte associado a uma tag de script específica do tema da apresentação.
type: docs
weight: 92
url: /pt/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) método

Obtém o nome da fonte associado a uma tag de script específica do tema da apresentação.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | O código de script BCP-47 (por exemplo, \"Latn\", \"Cyrl\", \"Jpan\") usado para identificar um sistema de escrita. |

### Valor de Retorno

O nome da fonte usada para o script especificado, ou **null** se o script não estiver definido.

## Observações

Este exemplo demonstra como recuperar a fonte atribuída ao script cirílico no tema da apresentação. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [IFonts](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)