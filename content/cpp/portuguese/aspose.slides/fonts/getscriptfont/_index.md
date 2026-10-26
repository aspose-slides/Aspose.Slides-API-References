---
title: GetScriptFont()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o nome da fonte associado a uma tag de script específica do tema da apresentação.
type: docs
weight: 92
url: /pt/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) método

Obtém o nome da fonte associado a uma tag de script específica do tema da apresentação.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | O código de script BCP-47 (por exemplo, \"Latn\", \"Cyrl\", \"Jpan\") usado para identificar um sistema de escrita. |

### Valor de retorno

O nome da fonte usada para o script especificado, ou **null** se o script não estiver definido.

## Observações

Este exemplo demonstra como recuperar a fonte atribuída ao script Cyrillic no tema da apresentação.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Veja também

* Classe [String](../../../system/string/)
* Classe [Fonts](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)