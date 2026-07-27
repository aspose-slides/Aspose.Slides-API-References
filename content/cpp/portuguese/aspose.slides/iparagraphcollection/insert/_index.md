---
title: Insert()
second_title: Referência da API Aspose.Slides para C++
description: Insere um Paragraph na coleção no índice especificado.
type: docs
weight: 40
url: /pt/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) método

Insere um [Paragraph](../../paragraph/) na coleção no índice especificado.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual [Paragraph](../../paragraph/) deve ser inserido. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | O [Paragraph](../../paragraph/) a ser inserido. |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) método

Insere um conteúdo de [ParagraphCollection](../../paragraphcollection/) na coleção no índice especificado.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual parágrafos devem ser inseridos. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | Os parágrafos a serem inseridos. |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraph](../../iparagraph/)
* Classe [IParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)