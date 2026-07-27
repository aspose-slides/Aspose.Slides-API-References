---
title: "System::Runtime::Serialization"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 794
url: /pt/system.runtime.serialization/
---
## Classes

| Class | Descrição |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Representa uma implementação base da interface [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | Fornece a conexão entre uma instância de [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) e a classe fornecida pelo formatador mais adequada para analisar os dados dentro de [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Interface de objeto que pode ser serializado. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use este ponteiro para passá-lo a funções como argumento. |
| [SerializationInfo](./serializationinfo/) | Contém um conjunto de campos nomeados que representam um objeto serializado. Não implementado. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use este ponteiro para passá-lo a funções como argumento. |
| [StreamingContext](./streamingcontext/) | Classe fictícia para permitir a compilação de classes traduzidas que utilizam StreamingContext. Não gerencie instâncias desta classe por [SmartPtr](../system/smartptr/), elas devem ser alocadas apenas na pilha. |
## Typedefs

| Typedef | Descrição |
| --- | --- |
| [SerializationException](./serializationexception/) |  |