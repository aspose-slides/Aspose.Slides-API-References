---
title: DbProviderFactories
second_title: Aspose.Slides para C++ Referência da API
description: "API para obter fábricas de provedores DB. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 53
url: /pt/system.data.common/dbproviderfactories/
---
## DbProviderFactories classe

API para obter fábricas de provedores DB. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class DbProviderFactories
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Obtém a fábrica de provedores DB pelo nome. |
## Ver também

* Espaço de nomes [System::Data::Common](../)
* Biblioteca [Aspose.Slides](../../)