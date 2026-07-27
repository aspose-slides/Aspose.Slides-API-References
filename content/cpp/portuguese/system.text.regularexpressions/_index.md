---
title: "System::Text::RegularExpressions"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 989
url: /pt/system.text.regularexpressions/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [Capture](./capture/) | Resultado de correspondência de subexpressão única. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la às funções como argumento. |
| [CaptureCollection](./capturecollection/) | Lista de capturas realizadas por um único grupo de captura. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la às funções como argumento. |
| [Group](./group/) | Resultado de correspondência feita por um único grupo de captura. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la às funções como argumento. |
| [GroupCollection](./groupcollection/) | Lista de grupos de captura em uma única correspondência. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la às funções como argumento. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) ponteiro de coleção. Este tipo é um ponteiro para gerenciar a exclusão de outros objetos. Deve ser alocado na pilha e passado às funções por valor ou por referência constante. |
| [Match](./match/) | [Single](../system/single/) correspondência de expressão regular sobre a string. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la às funções como argumento. |
| [MatchCollection](./matchcollection/) | Coleção de correspondências obtidas ao aplicar repetidamente expressão regular à string. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la às funções como argumento. |
| [Regex](./regex/) | Expressão regular que segue sintaxe semelhante à do C#. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la às funções como argumento. |
## Funções

| Função | Descrição |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Invólucro para manter a classe MatchHolder sem sua inclusão, bem como PCRE2. |
## Enumerações

| Enumeração | Descrição |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) opções. |
## Definições de Tipo

| Definição de Tipo | Descrição |
| --- | --- |
| [UStringPtr](./ustringptr/) | UnicodeString compartilhada para evitar cópias. |
| [CapturePtr](./captureptr/) | Ponteiro para objeto de captura único. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Ponteiro para coleção de captura. |
| [GroupPtr](./groupptr/) | Ponteiro para grupo. |
| [RegexPtr](./regexptr/) | ponteiro [Regex](./regex/). |
| [MatchPtr](./matchptr/) | ponteiro [Match](./match/). |
| [MatchCollectionPtr](./matchcollectionptr/) | ponteiro de coleção [Match](./match/). |
| [MatchEvaluator](./matchevaluator/) | Tipo delegate para avaliar correspondência. |