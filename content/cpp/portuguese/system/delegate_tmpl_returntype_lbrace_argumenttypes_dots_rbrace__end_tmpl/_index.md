---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides para C++ Referência da API
description: "Representa um ponteiro para uma função, método ou um objeto de função. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 287
url: /pt/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> classe

Representa um ponteiro para uma função, método ou um objeto de função. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use [System::SmartPtr](../smartptr/) classe para gerenciar objetos desse tipo.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ReturnType | O tipo de retorno de uma função, método ou ponteiro para objeto de função representado pela classe |
| ArgumentTypes | A lista de argumentos de uma função, método ou ponteiro para objeto de função representado pela classe |
## Métodos

| Método | Descrição |
| --- | --- |
|  [Delegate](./delegate/)() | Construtor padrão. Constrói o objeto delegate que não aponta para nada. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Construtor de cópia em movimento. Assume a propriedade de uma entidade apontada pelo delegate especificado. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Construtor. Constrói um objeto delegate a partir do ponteiro especificado para uma função livre ou método estático. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Construtor. Constrói um delegate a partir do ponteiro especificado para o objeto função gerado por std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Construtor. Constrói um delegate a partir do objeto função especificado. |
|  [Delegate](./delegate/)(long, T\&&) | Construtor em movimento. Constrói um delegate a partir do objeto função especificado. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Construtor. Constrói um delegate que aponta para o método não estático especificado do objeto especificado. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Construtor. Constrói um delegate que aponta para o método não estático especificado do objeto especificado. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Constrói um objeto delegate que aponta para um objeto função std::function. |
| **bool** [Empty](./empty/)() const | Determina se o objeto delegate atual está vazio, por exemplo, não aponta para nenhuma entidade. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invoca uma função, método ou um objeto de função apontado pelo objeto delegate atual. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Operador de atribuição em movimento. Assume a propriedade de uma entidade apontada pelo delegate especificado. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Compara dois objetos delegate para verificar se apontam para a mesma entidade. |
## Observações

```cpp
#include "system/delegate.h"
#include <iostream"

// Declara o delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Atribui à variável o endereço da função PrintMessage.
  Message mes = Message(&PrintMessage);

  // Chama a função.
  mes();

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
Hello, world!
*/
```

## Ver também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)