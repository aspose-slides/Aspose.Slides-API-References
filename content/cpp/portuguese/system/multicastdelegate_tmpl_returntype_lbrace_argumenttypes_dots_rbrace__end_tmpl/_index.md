---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Referência da API Aspose.Slides para C++
description: "Representa uma coleção de delegates. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 1093
url: /pt/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> classe


Representa uma coleção de delegates. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use [System::SmartPtr](../smartptr/) classe para gerenciar objetos deste tipo.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ReturnType | Tipo de retorno das entidades invocáveis apontadas por cada delegate na coleção |
| ArgumentTypes | Lista de argumentos das entidades invocáveis apontadas por cada delegate na coleção |
## Métodos

| Método | Descrição |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NÃO IMPLEMENTADO. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Adiciona o delegate especificado à coleção. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Adiciona o objeto de função especificado à coleção de delegate. O objeto de função é convertido para o tipo delegate Callback antes de ser adicionado à coleção. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Adiciona o objeto MulticastDelegate especificado à coleção de delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Adiciona o método não estático especificado do objeto especificado à coleção de delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Adiciona o método não estático especificado do objeto especificado à coleção de delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Remove o delegate especificado da coleção de delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Remove o método não estático especificado do objeto especificado da coleção de delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Remove o método não estático especificado do objeto especificado da coleção de delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Remove o objeto MulticastDelegate especificado da coleção de delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Remove todos os delegates da coleção de delegate. |
| **bool** [empty](./empty/)() const | Determina se a coleção de delegate está vazia. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NÃO IMPLEMENTADO. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Invoca todos os delegates atualmente presentes na coleção de delegate. Os delegates são invocados na mesma ordem em que foram adicionados à coleção. O método bloqueia enquanto os delegates são executados. |
| **bool** [IsNull](./isnull/)() const | Determina se a coleção de delegate está vazia. |
|  [MulticastDelegate](./multicastdelegate/)() | Constrói uma coleção vazia. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Equivalente ao construtor padrão. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Realiza uma cópia superficial da coleção de delegate. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Construtor de movimentação. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Constrói uma instância e adiciona o delegate especificado à coleção de delegate. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Constrói uma instância e adiciona o valor especificado à coleção de delegate. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Constrói uma instância e adiciona o valor especificado à coleção de delegate. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Determina se a coleção de delegate não está vazia. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Determina se duas instâncias de MulticastDelegate - o objeto atual e o objeto especificado - são diferentes. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invoca todos os delegates atualmente presentes na coleção de delegate. Os delegates são invocados na mesma ordem em que foram adicionados à coleção. O operador bloqueia enquanto os delegates são executados. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Adiciona o delegate especificado à coleção. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Remove o delegate especificado da coleção de delegate. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Atribui a coleção de delegates representada pelo objeto especificado ao objeto atual. Como resultado, ambos os objetos apontam para a mesma coleção de delegates. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Operador de atribuição por movimentação. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Determina se a coleção de delegate está vazia. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Determina se duas instâncias de MulticastDelegate - o objeto atual e o objeto especificado - são iguais. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Limpa os callbacks contidos que estão vazios (não chamando nada). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retorna uma referência ao objeto [TypeInfo](../typeinfo/) que representa as informações de tipo da classe MulticastDelegate. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destrutor. |
## Typedefs

| Typedef | Descrição |
| --- | --- |
| [Callback](./callback/) | O tipo dos delegates representados pela classe MulticastDelegate. |
| [Function](./function/) | O tipo da função relacionado à assinatura do delegate. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)