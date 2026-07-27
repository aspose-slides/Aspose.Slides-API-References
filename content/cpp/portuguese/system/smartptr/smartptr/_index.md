---
title: SmartPtr()
second_title: Referência da API Aspose.Slides para C++
description: Cria objeto SmartPtr do modo requerido.
type: docs
weight: 1
url: /pt/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) construtor


Cria objeto [SmartPtr](../) do modo requerido.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo do ponteiro. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) construtor


Cria objeto [SmartPtr](../) de ponteiro nulo do modo requerido.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mode | std::nullptr_t | Modo do ponteiro. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) construtor


Cria [SmartPtr](../) apontando para o objeto especificado, ou converte ponteiro bruto para [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo do ponteiro. |

## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) construtor


Constrói uma cópia do objeto [SmartPtr](../). Ambos os ponteiros apontam para o mesmo objeto depois.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Ponteiro a ser copiado. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo do ponteiro. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) construtor


Constrói uma cópia do objeto [SmartPtr](../). Ambos os ponteiros apontam para o mesmo objeto depois. Realiza conversão de tipo se permitido.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parâmetros de template

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo do objeto apontado por x. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Ponteiro a ser copiado. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo do ponteiro. |

## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) construtor


Constrói uma movimentação do objeto [SmartPtr](../). Efetivamente, troca dois ponteiros, se ambos estiverem no mesmo modo. x pode ficar inutilizável após a chamada.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Ponteiro a ser movido. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo do ponteiro. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) construtor


Converte o tipo da matriz referenciada criando uma nova matriz de tipo diferente. Útil se em C# houver uma conversão de tipo de matriz que não é suportada em C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parâmetros de template

| Parâmetro | Descrição |
| --- | --- |
| Y | Tipo da matriz fonte. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Ponteiro para a matriz a ser copiada, mas com tipo diferente de elementos. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo do ponteiro. |

## SmartPtr::SmartPtr(const Y\&) construtor


Inicializa uma matriz vazia. Usado para traduzir alguns constructos de código C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Parâmetros de template

| Parâmetro | Descrição |
| --- | --- |
| Y | Placeholder do tipo EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) construtor


Constrói um [SmartPtr](../) que compartilha informações de propriedade com o valor inicial de ptr, mas mantém um ponteiro não relacionado e não gerenciado p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Outro smart pointer que compartilha a propriedade. |
| p | [Pointee_](../pointee_/) * | Ponteiro para um objeto a ser gerenciado. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo do ponteiro. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream"

// Esta classe contém um campo que será impresso.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Esta classe contém uma instância da classe Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Usado para imprimir uma string da instância da classe Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Imprime o número de ponteiros compartilhados que apontam para o objeto.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Cria SharedPtr para uma instância da classe Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Cria SharedPtr que apontará para o campo da instância da classe Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Faz o ponteiro 'bar' apontar para nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data ainda existe e o ponteiro 'foo' é válido.
  PrintMessage(foo);

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
Número de ponteiros compartilhados: 1
Número de ponteiros compartilhados: 2
Número de ponteiros compartilhados: 0
Olá, mundo!
*/
``` |

## Veja Também

* Enumeração [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Classe [SmartPtr](../)
* Classe [Array](../../array/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)