---
title: SmartPtr
second_title: "Referência da API Aspose.Slides para C++"
description: "Classe ponteiro para envolver tipos alocados no heap. Use-a para gerenciar memória de classes que herdam Object. Este tipo de ponteiro segue a semântica de ponteiro intrusivo. O contador de referência é armazenado ou no próprio Object ou em estrutura de contador que está estreitamente ligada à instância Object. Em qualquer caso, todas as instâncias SmartPtr formam um grupo de propriedade única, independentemente de como foram criadas, o que difere do comportamento da classe std::shared_ptr. Converter ponteiro bruto para SmartPtr é seguro, visto que há outras instâncias SmartPtr mantendo referências compartilhadas ao mesmo objeto. Instância da classe SmartPtr pode estar em um dos dois estados: ponteiro compartilhado e ponteiro fraco. Para manter o objeto vivo, deve haver um número positivo de referências compartilhadas a ele. Tanto ponteiros fracos quanto compartilhados podem ser usados para acessar o objeto apontado (para chamar métodos, ler ou escrever campos, etc.), mas ponteiros fracos não participam da contagem de referências do ponteiro compartilhado. Object é deletado quando o último ponteiro 'shared' SmartPtr para ele é destruído. Portanto, certifique-se de que isso não aconteça quando não existirem outros ponteiros SmartPtr compartilhados para o objeto, por exemplo, durante a construção ou destruição do objeto. Use objetos sentinela System::Object::ThisProtector (no código C++) ou atributos CppCTORSelfReference ou CppSelfReference (no código C# sendo traduzido) para corrigir esse problema. De forma similar, garanta a quebra de referências cíclicas usando a classe de ponteiro System::WeakPtr ou o modo System::SmartPtrMode::Weak (no código C++) ou o atributo CppWeakPtr (no código C# sendo traduzido). Se dois ou mais objetos se referenciam mutuamente usando ponteiros 'shared', eles nunca serão deletados. Se o tipo de ponteiro (fraco ou compartilhado) precisar ser alterado em tempo de execução, use o método System::SmartPtr<T>::set_Mode() ou a classe System::DynamicWeakPtr. A classe SmartPtr não contém nenhum método virtual. Você só deve herdá-la se estiver criando sua própria estratégia de gerenciamento de memória. Este tipo é um ponteiro para gerenciar a exclusão de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante."
type: docs
weight: 1236
url: /pt/system/smartptr/
---
## SmartPtr classe

Classe ponteiro para envolver tipos alocados no heap. Use-a para gerenciar memória de classes que herdam [Object](../object/). Este tipo de ponteiro segue a semântica de ponteiro intrusivo. O contador de referência é armazenado ou em [Object](../object/) próprio ou em uma estrutura de contador que está fortemente ligada à instância [Object](../object/). Em qualquer caso, todas as instâncias [SmartPtr](./) formam um grupo de propriedade única, independentemente de como foram criadas, o que difere do comportamento da classe std::shared_ptr. Converter um ponteiro bruto para [SmartPtr](./) é seguro, dado que existem outras instâncias [SmartPtr](./) mantendo referências compartilhadas ao mesmo objeto. Uma instância da classe [SmartPtr](./) pode estar em um dos dois estados: ponteiro compartilhado e ponteiro fraco. Para manter o objeto vivo, deve haver um número positivo de referências compartilhadas a ele. Tanto ponteiros fracos quanto compartilhados podem ser usados para acessar o objeto apontado (para chamar métodos, ler ou escrever campos, etc.), mas ponteiros fracos não participam da contagem de referências do ponteiro compartilhado. [Object](../object/) é deletado quando o último ponteiro 'shared' [SmartPtr](./) para ele é destruído. Portanto, certifique-se de que isso não aconteça quando não existirem outros ponteiros [SmartPtr](./) compartilhados para o objeto, por exemplo, durante a construção ou destruição do objeto. Use os objetos sentinela System::Object::ThisProtector (no código C++) ou o atributo CppCTORSelfReference ou CppSelfReference (no código C# sendo traduzido) para corrigir este problema. De forma similar, assegure-se de interromper referências cíclicas usando a classe de ponteiro [System::WeakPtr](../weakptr/) ou o modo de ponteiro [System::SmartPtrMode::Weak](../smartptrmode/) (no código C++) ou o atributo CppWeakPtr (no código C# sendo traduzido). Se dois ou mais objetos se referenciam mutuamente usando ponteiros 'shared', eles nunca serão deletados. Se o tipo de ponteiro (fraco ou compartilhado) precisar ser alterado em tempo de execução, use o método [System::SmartPtr<T>::set_Mode()](./set_mode/) ou a classe [System::DynamicWeakPtr](../dynamicweakptr/). A classe [SmartPtr](./) não contém nenhum método virtual. Você só deve herdá-la se estiver criando sua própria estratégia de gerenciamento de memória. Este tipo é um ponteiro para gerenciar a exclusão de outro objeto. Ele deve ser alocado na pilha e passado para funções por valor ou por referência constante.

```cpp
template<class T>class SmartPtr
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do objeto apontado. Deve ser [System::Object](../object/) ou uma subclasse dele. |

## Métodos

| Método | Descrição |
| --- | --- |
| auto [begin](./begin/)() | Acessador para o método [begin()](./begin/) de uma coleção subjacente. Compila somente se SmartPtr_ for um tipo de especialização com o método [begin()](./begin/). |
| auto [begin](./begin/)() const | Acessador para o método [begin()](./begin/) de uma coleção subjacente. Compila somente se SmartPtr_ for um tipo de especialização com o método [begin()](./begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Converte o ponteiro para seu próprio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Converte o ponteiro para o tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Converte o ponteiro para o tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Converte o ponteiro para o tipo derivado usando dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Acessador para o método [cbegin()](./cbegin/) de uma coleção subjacente. Compila somente se SmartPtr_ for um tipo de especialização com o método [cbegin()](./cbegin/). |
| auto [cend](./cend/)() const | Acessador para o método [cend()](./cend/) de uma coleção subjacente. Compila somente se SmartPtr_ for um tipo de especialização com o método [cend()](./cend/). |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando const_cast no objeto apontado. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando dynamic_cast no objeto apontado. |
| auto [end](./end/)() | Acessador para o método [end()](./end/) de uma coleção subjacente. Compila somente se SmartPtr_ for um tipo de especialização com o método [end()](./end/). |
| auto [end](./end/)() const | Acessador para o método [end()](./end/) de uma coleção subjacente. Compila somente se SmartPtr_ for um tipo de especialização com o método [end()](./end/). |
| [Pointee_](./pointee_/) * [get](./get/)() const | Obtém o objeto apontado. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Obtém o modo do ponteiro. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Obtém o objeto apontado, mas garante que o ponteiro está em modo compartilhado. |
| int [get_shared_count](./get_shared_count/)() const | Obtém o número de ponteiros compartilhados existentes para o objeto referenciado, incluindo o atual. Garante que o ponteiro atual esteja em modo compartilhado. |
| int [GetHashCode](./gethashcode/)() const | Chama [GetHashCode()](./gethashcode/) no objeto apontado. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Obtém o objeto atualmente referenciado (se houver) ou lança exceção. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Obtém o objeto apontado (se houver) ou nullptr. Equivalente a [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Obtém o objeto referenciado. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Obtém o objeto apontado (se houver) ou nullptr. Equivalente a [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Verifica se o objeto apontado é de um tipo específico ou de seu tipo filho. Segue a semântica 'is' do C#. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Verifica se o ponteiro aponta para um objeto diferente do próprio (criado por um construtor de aliasing). |
| **bool** [IsShared](./isshared/)() const | Verifica se o ponteiro está em modo compartilhado. |
| **bool** [IsWeak](./isweak/)() const | Verifica se o ponteiro está em modo fraco. |
| explicit  [operator bool](./operator_bool/)() const | Verifica se o ponteiro não é nulo. |
| **bool** [operator!](./operator_not/)() const | Verifica se o ponteiro é nulo. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Obtém referência ao objeto apontado. Garante que o ponteiro não seja nulo. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Permite acessar membros do objeto referenciado. |
| **bool** [operator<](./operator_less/)(Y *) const | Fornece semântica de comparação menor para a classe [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Fornece semântica de comparação menor para a classe [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Move-atribui o objeto [SmartPtr](./). x torna-se inutilizável. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Copia-atribui o objeto [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Copia-atribui o objeto [SmartPtr](./). Executa as conversões de tipo necessárias. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Atribui ponteiro bruto ao objeto [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Define o valor do ponteiro como nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se o ponteiro aponta para nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Remove o aliasing (criado por um construtor de aliasing) do ponteiro, assegurando que ele gerencia (se compartilhado) ou rastreia (se fraco) o mesmo objeto ao qual aponta. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Define o objeto apontado. |
| void [reset](./reset/)() | Faz o ponteiro apontar para nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Define o modo do ponteiro. Pode alterar as contagens de referência do objeto referenciado. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Chama o método SetTemplateWeakPtr() no objeto apontado (se houver). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Cria um objeto [SmartPtr](./) do modo requerido. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Cria um objeto [SmartPtr](./) de ponteiro nulo no modo requerido. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Cria um [SmartPtr](./) apontando para o objeto especificado, ou converte ponteiro bruto para [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Constrói por cópia o objeto [SmartPtr](./). Ambos os ponteiros apontam para o mesmo objeto depois. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Constrói por cópia o objeto [SmartPtr](./). Ambos os ponteiros apontam para o mesmo objeto depois. Executa conversão de tipo se permitida. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Move-constrói o objeto [SmartPtr](./). Efetivamente, troca dois ponteiros, se ambos estiverem no mesmo modo. x pode ficar inutilizável após a chamada. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converte o tipo da matriz referenciada criando uma nova matriz de tipo diferente. Útil se em C# houver um cast de tipo de array que não é suportado em C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Inicializa uma matriz vazia. Usado para traduzir alguns constructos de código C#. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Constrói um [SmartPtr](./) que compartilha informações de propriedade com o valor inicial de ptr, mas mantém um ponteiro p não relacionado e não gerenciado. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando static_cast no objeto apontado. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Converte qualquer tipo de ponteiro para ponteiro a [Object](../object/). Não requer que o tipo Pointee_ esteja completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Atalho para obter o objeto [System::TypeInfo](../typeinfo/) para o tipo Pointee_. |
|  [~SmartPtr](./~smartptr/)() | Destrói o objeto [SmartPtr](./). Se necessário, diminui o contador de referência do objeto apontado e o exclui. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Pointee_](./pointee_/) | Tipo apontado. |
| [SmartPtr_](./smartptr_/) | Tipo de ponteiro inteligente especializado. |
| [ArrayType](./arraytype/) | Mesmo que Pointee_, se for uma especialização de [System::Array](../array/), caso contrário void. |
| [ValueType](./valuetype/) | Tipo de armazenamento da matriz apontada. Só tem sentido se T for uma especialização de [System::Array](../array/). |

## Veja também

* Namespace [System](../)
* Library [Aspose.Slides](../../)