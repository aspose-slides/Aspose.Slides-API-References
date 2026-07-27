---
title: CollectionsToMsg()
second_title: Referência da API Aspose.Slides para C++
description: Serializa duas coleções para representação de mensagem.
type: docs
weight: 53
url: /pt/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method


Serializa duas coleções para representação de mensagem.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Expected collection element type. |
| T2 | Actual collection element type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | A custom string which is inserted before the expected value in the resulting message |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Expected collection. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Actual collection. |

### Valor de Retorno

Mensagem amigável sobre o conteúdo das coleções.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Estrutura [CollectionAssertHelper](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)