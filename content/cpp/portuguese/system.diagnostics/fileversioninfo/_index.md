---
title: FileVersionInfo
second_title: Referência da API Aspose.Slides para C++
description: "Fornece informações sobre a versão do arquivo. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 1
url: /pt/system.diagnostics/fileversioninfo/
---
## FileVersionInfo classe

Fornece informações sobre a versão do arquivo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class FileVersionInfo
```

## Métodos

| Método | Descrição |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Obtém o campo de versão do produto. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Obtém informações da versão do arquivo; não implementado. |
## Veja Também

* Namespace [System::Diagnostics](../)
* Biblioteca [Aspose.Slides](../../)