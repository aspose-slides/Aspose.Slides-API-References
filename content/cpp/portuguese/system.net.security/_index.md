---
title: "System::Net::Security"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 716
url: /pt/system.net.security/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Contém os métodos para passar credenciais através de um fluxo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo às funções como argumento. |
| [SslStream](./sslstream/) | Um fluxo que usa o protocolo SSL para autenticar o servidor e, opcionalmente, o cliente. |
## Enumerações

| Enumeração | Descrição |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Sinalizadores de autenticação específicos do WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Enumera os erros de política do SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Enumera as políticas de criptografia. |
## Definições de Tipo

| Definição de Tipo | Descrição |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Um delegate do usuário usado para verificar o certificado SSL remoto. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Um delegate do usuário usado para selecionar o certificado SSL local. |
