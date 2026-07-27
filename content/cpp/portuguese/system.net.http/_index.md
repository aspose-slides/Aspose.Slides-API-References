---
title: "System::Net::Http"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 677
url: /pt/system.net.http/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Representa o conteúdo HTTP como um array de bytes. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [Details_HttpRequestException](./details_httprequestexception/) | A classe base de exceção é lançada pelas classes [HttpClient](./httpclient/) e [HttpMessageHandler](./httpmessagehandler/). Nunca crie instâncias desta classe manualmente. Use a classe HttpRequestException em seu lugar. Nunca encapsule as instâncias da classe HttpRequestException em [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Representa uma classe base de um cliente HTTP para enviar requisições e receber respostas. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [HttpClientHandler](./httpclienthandler/) | Representa o manipulador de mensagem padrão usado pela classe [HttpClient](./httpclient/). Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [HttpContent](./httpcontent/) | Representa o conteúdo de uma entidade HTTP. [Object](../system/object/) desta classe deve ser alocado apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [HttpMessageHandler](./httpmessagehandler/) | Representa um tipo base para os manipuladores de mensagens HTTP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Permite que aplicações chamem o método Send em uma cadeia de manipuladores HTTP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [HttpMethod](./httpmethod/) | Representa um método HTTP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [HttpRequestMessage](./httprequestmessage/) | Representa uma mensagem de requisição HTTP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [HttpResponseMessage](./httpresponsemessage/) | Representa uma mensagem de resposta HTTP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [HttpUtilities](./httputilities/) | Contém os métodos utilitários. |
| [StringContent](./stringcontent/) | Representa o conteúdo HTTP como uma string. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |

## Funções

| Função | Descrição |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## Enumerações

| Enum | Descrição |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Indica quando uma operação [HttpClient](./httpclient/) deve ser concluída. |
| [HttpParseResult](./httpparseresult/) | Indica o resultado da análise. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |