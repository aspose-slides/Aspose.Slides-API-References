---
title: "System::Security"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 807
url: /pt/system.security/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | String segura, representa texto que deve ser mantido confidencial. Esta classe NÃO ENCRIPTA os dados internos. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [SecureStringMarshal](./securestringmarshal/) | Coleção de métodos para alocar e copiar blocos de memória não gerenciados. |
| [SecurityElement](./securityelement/) | Modelo de objeto XML para codificar objeto de segurança. Não implementado. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) tipo de ponteiro. |
