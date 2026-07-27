---
title: RemoveScriptFont()
second_title: Referência da API Aspose.Slides para C++
description: Remove a configuração de fonte associada a uma tag de script específica da coleção de fontes do tema.
type: docs
weight: 118
url: /pt/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) método

Remove a configuração de fonte associada a uma tag de script específica da coleção de fontes do tema.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | O código de script BCP-47 cuja configuração de fonte deve ser removida. |
## Observações

Este exemplo demonstra como remover o mapeamento de fonte para o script Hebraico:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [IFonts](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)