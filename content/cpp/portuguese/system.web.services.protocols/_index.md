---
title: "System::Web::Services::Protocols"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 1080
url: /pt/system.web.services.protocols/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Representa a exceção lançada quando o método é chamado via SOAP e ocorre um erro. Nunca crie instâncias desta classe manualmente. Use a classe SoapException em vez disso. Nunca encapsule as instâncias da classe SoapException em [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Esta classe base é usada em todos os proxies de cliente de serviço XML [Web](../system.web/) que utilizam HTTP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Uma instância desta classe é passada como argumento para o delegate InvokeCompletedEventHandler. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [SoapClientMessage](./soapclientmessage/) | Representa os dados em uma requisição SOAP enviada ou em uma resposta SOAP recebida. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Especifica que todas as mensagens SOAP passadas ou retornadas pelo método utilizam o formato Document. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Define o formato padrão para as requisições e respostas SOAP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [SoapHeader](./soapheader/) | Representa o conteúdo do cabeçalho SOAP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Especifica o cabeçalho SOAP que o método de serviço XML [Web](../system.web/) ou o cliente de serviço XML [Web](../system.web/) podem processar. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [SoapHeaderCollection](./soapheadercollection/) | Contém uma coleção de instâncias da classe [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | Os serviços de proxy de cliente devem herdar esta classe quando o SOAP é usado. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [SoapMessage](./soapmessage/) | Representa a mensagem SOAP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |
| [WebClientProtocol](./webclientprotocol/) | Esta classe base é usada em todos os proxies de cliente de serviço XML [Web](../system.web/) que foram criados usando ASP.NET. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo para funções como argumento. |

## Enumerações

| Enumeração | Descrição |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Enumera as direções do cabeçalho SOAP. |
| [SoapMessageStage](./soapmessagestage/) | Enumera as etapas de processamento das mensagens SOAP. |
| [SoapParameterStyle](./soapparameterstyle/) | Enumera os formatos dos parâmetros em uma mensagem SOAP. |
| [SoapProtocolVersion](./soapprotocolversion/) | Enumera as versões do SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Enumera opções de como uma mensagem SOAP é roteada para o serviço XML [Web](../system.web/). |

## Definições de Tipo

| Definição de Tipo | Descrição |
| --- | --- |
| [SoapException](./soapexception/) |  |