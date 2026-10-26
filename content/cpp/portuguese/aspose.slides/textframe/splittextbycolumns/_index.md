---
title: SplitTextByColumns()
second_title: Referência da API Aspose.Slides para C++
description: Divide o conteúdo de texto do ITextFrame em um array de strings, onde cada elemento corresponde a uma coluna de texto separada dentro da moldura.
type: docs
weight: 144
url: /pt/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() método

Divida o conteúdo de texto do [ITextFrame](../../itextframe/) em um array de strings,

 onde cada elemento corresponde a uma coluna de texto separada dentro da moldura.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### Valor de Retorno

Um array de strings, onde cada string representa o conteúdo de texto de uma coluna específica

 no [ITextFrame](../../itextframe/).
## Observações

Se a moldura de texto não contiver múltiplas colunas, o array retornado terá um único elemento

 contendo o texto completo.

 Colunas vazias serão representadas como strings vazias no array.

O exemplo a seguir demonstra como usar o [TextFrame::SplitTextByColumns](./):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Obtenha a primeira forma no slide e converta-a para ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Divida o conteúdo da moldura de texto em colunas
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Imprima o texto de cada coluna no console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [TextFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)