---
title: FoundResult()
second_title: Referência da API Aspose.Slides para C++
description: Método de callback que recebe dados sobre o texto encontrado.
type: docs
weight: 1
url: /pt/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) método

Método de callback que recebe dados sobre o texto encontrado.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | O [ITextFrame](../../itextframe/) em que o texto foi encontrado. |
| sourceText | [System::String](../../../system/string/) | O texto fonte em que o texto foi encontrado. |
| foundText | [System::String](../../../system/string/) | O texto encontrado. |
| textPosition | **int32_t** | A posição do texto encontrado. |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../itextframe/)
* Classe [String](../../../system/string/)
* Classe [IFindResultCallback](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)