---
title: Contains()
second_title: Aspose.Slides para C++ Referência da API
description: Determina se a coleção contém um valor específico.
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) método


Determina se a coleção contém um valor específico.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | O objeto a localizar na coleção. |

### Valor de retorno

verdadeiro se *mathBlock* for encontrado na coleção; caso contrário, falso.
## Observações



Exemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)