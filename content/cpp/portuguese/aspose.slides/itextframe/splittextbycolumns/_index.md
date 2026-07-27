---
title: SplitTextByColumns()
second_title: Referência da API Aspose.Slides para C++
description: Divide o conteúdo de texto do ITextFrame em um array de strings, onde cada elemento corresponde a uma coluna de texto separada dentro da moldura.
type: docs
weight: 118
url: /pt/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() method


Divide o conteúdo de texto do [ITextFrame](../) em um array de strings, 

 onde cada elemento corresponde a uma coluna de texto separada dentro da moldura.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Valor de retorno

Um array de strings, onde cada string representa o conteúdo de texto de uma coluna específica no [ITextFrame](../).
## Observações



Se a moldura de texto não contiver várias colunas, o array retornado terá um único elemento contendo o texto completo. 

 Colunas vazias serão representadas como strings vazias no array. 

O exemplo a seguir demonstra como usar [ITextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Obtém a primeira forma no slide e converte-a para ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Divide o conteúdo da moldura de texto em colunas
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Imprime o texto de cada coluna no console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)