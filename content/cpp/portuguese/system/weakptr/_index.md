---
title: WeakPtr
second_title: Referência da API Aspose.Slides para C++
description: "Subclasse de System::SmartPtr que se define em modo fraco na construção. Observe que esta classe não garante que sua instância permanecerá sempre em modo fraco, pois set_Mode() ainda está acessível. Este tipo é um ponteiro para gerenciar a exclusão de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante."
type: docs
weight: 1496
url: /pt/system/weakptr/
---
## WeakPtr classe

Subclasse de [System::SmartPtr](../smartptr/) que define a si mesma em modo fraco na construção. Observe que esta classe não garante que sua instância permanecerá sempre em modo fraco, pois [set_Mode()](../smartptr/set_mode/) ainda está acessível. Este tipo é um ponteiro para gerenciar a exclusão de outro objeto. Deve ser alocado na pilha e passado para funções por valor ou por referência constante.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo apontado. |

## Métodos

| Método | Descrição |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Acessor do método [begin()](../smartptr/begin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Acessor do método [begin()](../smartptr/begin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte o ponteiro para o próprio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte o ponteiro para o tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte o ponteiro para o tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte o ponteiro para o tipo derivado usando dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Acessor do método [cbegin()](../smartptr/cbegin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Acessor do método [cend()](../smartptr/cend/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando const_cast no objeto apontado. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando dynamic_cast no objeto apontado. |
| auto [end](../smartptr/end/)() | Acessor do método [end()](../smartptr/end/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Acessor do método [end()](../smartptr/end/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Verifica se o objeto referenciado já foi excluído. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Obtém o objeto apontado. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Obtém o modo do ponteiro. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Obtém o objeto apontado, mas verifica se o ponteiro está em modo compartilhado. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Obtém o número de ponteiros compartilhados existentes para o objeto referenciado, incluindo o atual. Verifica se o ponteiro atual está em modo compartilhado. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Obtém o objeto referenciado. Verifica se o ponteiro está em modo fraco. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Chama [GetHashCode()](../smartptr/gethashcode/) no objeto apontado. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Obtém o objeto atualmente referenciado (se houver) ou lança exceção. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Obtém o objeto apontado (se houver) ou nullptr. Igual a [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Obtém o objeto referenciado. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Obtém o objeto apontado (se houver) ou nullptr. Igual a [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Verifica se o objeto apontado é de um tipo específico ou de seu tipo filho. Segue a semântica 'is' do C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Verifica se o ponteiro aponta para outro objeto que não o próprio (criado por um construtor de alias). |
| **bool** [IsShared](../smartptr/isshared/)() const | Verifica se o ponteiro está em modo compartilhado. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Verifica se o ponteiro está em modo fraco. |
| explicit [operator bool](../smartptr/operator_bool/)() const | Verifica se o ponteiro não é nulo. |
| **bool** [operator!](../smartptr/operator_not/)() const | Verifica se o ponteiro é nulo. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Obtém referência ao objeto apontado. Verifica se o ponteiro não é nulo. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Permite acessar membros do objeto referenciado. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Fornece semântica de comparação menor para a classe [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Fornece semântica de comparação menor para a classe [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Atribui valor ao ponteiro fraco. Chama o operador de atribuição específico de SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Move-atribui objeto [SmartPtr](../smartptr/). x torna-se inutilizável. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Copia-atribui objeto [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Copia-atribui objeto [SmartPtr](../smartptr/). Realiza as conversões de tipo necessárias. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Atribui ponteiro cru ao objeto [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Define o valor do ponteiro como nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se o ponteiro fraco é nulo. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Remove o alias (criado por um construtor de alias) do ponteiro, garantindo que ele gerencia (se compartilhado) ou rastreia (se fraco) o mesmo objeto ao qual aponta. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Define o objeto apontado. |
| void [reset](../smartptr/reset/)() | Faz o ponteiro apontar para nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Define o modo do ponteiro. Pode alterar as contagens de referência do objeto referenciado. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Chama o método SetTemplateWeakPtr() no objeto apontado (se houver). |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Cria objeto [SmartPtr](../smartptr/) no modo requerido. |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Cria objeto [SmartPtr](../smartptr/) de ponteiro nulo no modo requerido. |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Cria [SmartPtr](../smartptr/) apontando para o objeto especificado, ou converte ponteiro cru para [SmartPtr](../smartptr/). |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Constrói cópia do objeto [SmartPtr](../smartptr/). Ambos os ponteiros apontam para o mesmo objeto depois. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Constrói cópia do objeto [SmartPtr](../smartptr/). Ambos os ponteiros apontam para o mesmo objeto depois. Realiza conversão de tipo se permitido. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Move-constrói objeto [SmartPtr](../smartptr/). Efetivamente, troca dois ponteiros, se ambos estiverem no mesmo modo. x pode ficar inutilizável após a chamada. |
| explicit [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converte o tipo da matriz referenciada criando uma nova matriz de tipo diferente. Útil se em C# houver um cast de tipo de matriz que não é suportado em C++. |
| explicit [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inicializa matriz vazia. Usado para traduzir alguns constructos de código C#. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Constrói um [SmartPtr](../smartptr/) que compartilha informações de propriedade com o valor inicial de ptr, mas mantém um ponteiro p não relacionado e não gerenciado. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando static_cast no objeto apontado. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Converte qualquer tipo de ponteiro para ponteiro para [Object](../object/). Não requer que o tipo Pointee_ seja completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Atalho para obter objeto [System::TypeInfo](../typeinfo/) para o tipo Pointee_. |
| [WeakPtr](./weakptr/)(std::nullptr_t) | Cria ponteiro nulo. |
| [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Cria ponteiro fraco para o objeto fornecido. |
| [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Cria ponteiro fraco referenciando o mesmo ponteiro que ptr aponta. |
| [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Cria ponteiro fraco referenciando o mesmo ponteiro que x aponta. |
| [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Constrói cópia do ponteiro fraco. |
| [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Constrói cópia do ponteiro fraco. |
| [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Move-constrói ponteiro fraco. |
| [~SmartPtr](../smartptr/~smartptr/)() | Destroi objeto [SmartPtr](../smartptr/). Se necessário, diminui o contador de referência do objeto apontado e exclui o objeto. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Apelido para a classe [SmartPtr](../smartptr/) correspondente. |
| [WeakPtr_](./weakptr_/) | Apelido para o próprio tipo. |
| [Pointee_](./pointee_/) | Apelido para o tipo apontado. |

## Veja Também

* Classe [SmartPtr](../smartptr/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)