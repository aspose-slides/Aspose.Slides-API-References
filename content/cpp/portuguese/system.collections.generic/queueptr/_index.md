---
title: QueuePtr
second_title: Referência da API Aspose.Slides para C++
description: Ponteiro de fila. Este tipo é um ponteiro para gerenciar a exclusão de outro objeto. Deve ser alocado na pilha e passado para funções tanto por valor quanto por referência constante.
type: docs
weight: 482
url: /pt/system.collections.generic/queueptr/
---
## QueuePtr classe


[Queue](../queue/) ponteiro. Este tipo é um ponteiro para gerenciar a exclusão de outro objeto. Deve ser alocado na pilha e passado para funções tanto por valor quanto por referência constante.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Métodos

| Método | Descrição |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Acessor para o método [begin()](../../system/smartptr/begin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Acessor para o método [begin()](../../system/smartptr/begin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Converte o ponteiro para seu próprio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Converte o ponteiro para o tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Converte o ponteiro para o tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Converte o ponteiro para o tipo derivado usando dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Acessor para o método [cbegin()](../../system/smartptr/cbegin/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Acessor para o método [cend()](../../system/smartptr/cend/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando const_cast no objeto apontado. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando dynamic_cast no objeto apontado. |
| auto [end](../../system/smartptr/end/)() | Acessor para o método [end()](../../system/smartptr/end/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Acessor para o método [end()](../../system/smartptr/end/) de uma coleção subjacente. Compila apenas se SmartPtr_ for um tipo de especialização com o método [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Obtém o objeto apontado. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Obtém o modo do ponteiro. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Obtém o objeto apontado, mas afirma que o ponteiro está em modo compartilhado. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Obtém o número de ponteiros compartilhados existentes para o objeto referenciado, incluindo o atual. Afirma que o ponteiro atual está em modo compartilhado. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Chama [GetHashCode()](../../system/smartptr/gethashcode/) no objeto apontado. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Obtém o objeto atualmente referenciado (se houver) ou lança exceção. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Obtém o objeto apontado (se houver) ou nullptr. Igual a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Obtém o objeto referenciado. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Obtém o objeto apontado (se houver) ou nullptr. Igual a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto apontado é de um tipo específico ou de um tipo filho. Segue a semântica 'is' do C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Verifica se o ponteiro aponta para outro objeto que não o próprio (criado por um construtor de aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Verifica se o ponteiro está em modo compartilhado. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Verifica se o ponteiro está em modo fraco. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Verifica se o ponteiro não é nulo. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Verifica se o ponteiro é nulo. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Obtém referência ao objeto apontado. Afirma que o ponteiro não é nulo. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Permite acessar membros do objeto referenciado. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Fornece semântica de comparação menor para a classe [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Fornece semântica de comparação menor para a classe [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Move-atribui o objeto [SmartPtr](../../system/smartptr/). x torna-se inutilizável. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Copia-atribui o objeto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Copia-atribui o objeto [SmartPtr](../../system/smartptr/). Executa as conversões de tipo necessárias. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Atribui ponteiro bruto ao objeto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Define o valor do ponteiro como nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Verifica se o ponteiro aponta para nullptr. |
|  [QueuePtr](./queueptr/)() | Constrói ponteiro nulo. |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | Constrói ponteiro para fila específica. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Remove o aliasing (criado por um construtor de aliasing) do ponteiro, assegurando que ele gerencia (se compartilhado) ou rastreia (se fraco) o mesmo objeto ao qual aponta. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Define o objeto apontado. |
| void [reset](../../system/smartptr/reset/)() | Faz o ponteiro apontar para nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Define o modo do ponteiro. Pode alterar as contagens de referência do objeto referenciado. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Chama o método SetTemplateWeakPtr() no objeto apontado (se houver). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Cria objeto [SmartPtr](../../system/smartptr/) do modo requerido. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Cria objeto [SmartPtr](../../system/smartptr/) nulo do modo requerido. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Cria [SmartPtr](../../system/smartptr/) apontando para o objeto especificado, ou converte ponteiro bruto para [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Constrói por cópia o objeto [SmartPtr](../../system/smartptr/). Ambos os ponteiros apontam para o mesmo objeto depois. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Constrói por cópia o objeto [SmartPtr](../../system/smartptr/). Ambos os ponteiros apontam para o mesmo objeto depois. Executa conversão de tipo se permitida. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Constrói por movimento o objeto [SmartPtr](../../system/smartptr/). Efetivamente, troca dois ponteiros, se ambos estiverem no mesmo modo. x pode ficar inutilizável após a chamada. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converte o tipo do array referenciado criando um novo array de tipo diferente. Útil se em C# houver um cast de tipo de array que não é suportado em C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicializa um array vazio. Usado para traduzir algumas construções de código C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Constrói um [SmartPtr](../../system/smartptr/) que compartilha informações de propriedade com o valor inicial de ptr, mas mantém um ponteiro p não relacionado e não gerenciado. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Converte o ponteiro para um tipo diferente usando static_cast no objeto apontado. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converte qualquer tipo de ponteiro para ponteiro a [Object](../../system/object/). Não requer que o tipo Pointee_ esteja completo. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Atalho para obter o objeto [System::TypeInfo](../../system/typeinfo/) para o tipo Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Destroi o objeto [SmartPtr](../../system/smartptr/). Se necessário, diminui o contador de referência do objeto apontado e exclui o objeto. |

## Veja Também

* Classe [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)