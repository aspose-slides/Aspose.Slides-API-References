---
title: DynamicWeakPtr
second_title: Referência da API Aspose.Slides para C++
description: Classe de ponteiro inteligente que acompanha os modos de ponteiro dos argumentos de modelo do objeto armazenado e os atualiza após cada atribuição. Esse tipo é um ponteiro para gerenciar a exclusão de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante.
type: docs
weight: 781
url: /pt/system/dynamicweakptr/
---
## DynamicWeakPtr classe

Smart pointer class which tracks pointer modes of template arguments of stored object and updates them after each assignment. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| Pointee | type. |
| trunkMode | Mode of smart pointer itself, shared or weak. |
| weakLeafs | Indexes of template arguments of stored type which should be set to weak pointer mode. |

## Métodos

| Método | Descrição |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Acessor para o método [begin()](../smartptr/begin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Acessor para o método [begin()](../smartptr/begin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte o ponteiro para seu próprio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte o ponteiro para o tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte o ponteiro para o tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte o ponteiro para o tipo derivado usando dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Acessor para o método [cbegin()](../smartptr/cbegin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Acessor para o método [cend()](../smartptr/cend/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando const_cast no objeto apontado. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando dynamic_cast no objeto apontado. |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Cria um ponteiro inteligente nulo. |
| [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Cria um ponteiro inteligente apontando para o objeto fornecido. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Constrói um ponteiro inteligente por cópia. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Constrói um ponteiro inteligente por cópia. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Constrói um ponteiro inteligente por cópia. |
| [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Constrói um ponteiro inteligente por movimentação. |
| auto [end](../smartptr/end/)() | Acessor para o método [end()](../smartptr/end/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Acessor para o método [end()](../smartptr/end/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Obtém o objeto apontado. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Obtém o modo do ponteiro. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Obtém o objeto apontado, mas verifica se o ponteiro está no modo compartilhado. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Obtém o número de ponteiros compartilhados existentes para o objeto referenciado, incluindo o atual. Verifica se o ponteiro atual está no modo compartilhado. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Chama [GetHashCode()](../smartptr/gethashcode/) no objeto apontado. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Obtém o objeto referenciado atualmente (se houver) ou lança exceção. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Obtém o objeto apontado (se houver) ou nullptr. Equivalente a [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Obtém o objeto referenciado. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Obtém o objeto apontado (se houver) ou nullptr. Equivalente a [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Verifica se o objeto apontado é de um tipo específico ou de um tipo filho. Segue a semântica 'is' do C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Verifica se o ponteiro aponta para outro objeto que não o de propriedade (criado por um construtor de alias). |
| **bool** [IsShared](../smartptr/isshared/)() const | Verifica se o ponteiro está no modo compartilhado. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Verifica se o ponteiro está no modo fraco. |
| explicit [operator bool](../smartptr/operator_bool/)() const | Verifica se o ponteiro não é nulo. |
| **bool** [operator!](../smartptr/operator_not/)() const | Verifica se o ponteiro é nulo. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Obtém referência ao objeto apontado. Verifica se o ponteiro não é nulo. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Permite acessar membros do objeto referenciado. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Fornece semântica de comparação menor para a classe [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Fornece semântica de comparação menor para a classe [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Move-atribui o ponteiro inteligente. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Copia-atribui o ponteiro inteligente. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Copia-atribui o ponteiro inteligente. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Atribui o ponteiro inteligente. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Define o ponteiro inteligente como nulo. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se o ponteiro inteligente é nulo. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Remove o aliasing (criado por um construtor de alias) do ponteiro, assegurando que ele gerencia (se compartilhado) ou rastreia (se fraco) o mesmo objeto ao qual aponta. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Define o objeto apontado. |
| void [reset](../smartptr/reset/)() | Faz o ponteiro apontar para nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Define o modo do ponteiro. Pode alterar as contagens de referência do objeto referenciado. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Chama o método SetTemplateWeakPtr() no objeto apontado (se houver). |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Cria um objeto [SmartPtr](../smartptr/) no modo requerido. |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Cria um objeto [SmartPtr](../smartptr/) de ponteiro nulo no modo requerido. |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Cria um [SmartPtr](../smartptr/) apontando para o objeto especificado, ou converte ponteiro bruto para [SmartPtr](../smartptr/). |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Constrói por cópia o objeto [SmartPtr](../smartptr/). Ambos os ponteiros apontam para o mesmo objeto posteriormente. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Constrói por cópia o objeto [SmartPtr](../smartptr/). Ambos os ponteiros apontam para o mesmo objeto posteriormente. Realiza conversão de tipo se permitida. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Constrói por movimentação o objeto [SmartPtr](../smartptr/). Efetivamente, troca dois ponteiros, se ambos estiverem no mesmo modo. x pode ficar inutilizável após a chamada. |
| explicit [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converte o tipo do array referenciado criando um novo array de tipo diferente. Útil se em C# houver um cast de tipo de array que não é suportado em C++. |
| explicit [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inicializa um array vazio. Usado para traduzir alguns construtos de código C#. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Constrói um [SmartPtr](../smartptr/) que compartilha informações de propriedade com o valor inicial de ptr, mas mantém um ponteiro não relacionado e não gerenciado p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando static_cast no objeto apontado. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Converte qualquer tipo de ponteiro para ponteiro de [Object](../object/). Não requer que o tipo Pointee_ esteja completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Atalho para obter o objeto [System::TypeInfo](../typeinfo/) para o tipo Pointee_. |
| [~SmartPtr](../smartptr/~smartptr/)() | Destrói o objeto [SmartPtr](../smartptr/). Se necessário, diminui o contador de referência do objeto apontado e exclui o objeto. |

## Definições de tipo

| Definição | Descrição |
| --- | --- |
| [SmartPtr_](./smartptr_/) | alias da classe base [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/) | alias do tipo próprio. |
| [Pointee_](./pointee_/) | tipo apontado. |

## Veja Também

* Classe [SmartPtr](../smartptr/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)