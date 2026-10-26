---
title: SmartPtr()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea l'oggetto SmartPtr nella modalità richiesta.
type: docs
weight: 1
url: /it/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) costruttore

Crea l'oggetto [SmartPtr](../) della modalità richiesta.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Modalità del puntatore. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) costruttore

Crea l'oggetto [SmartPtr](../) puntatore nullo della modalità richiesta.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | std::nullptr_t | Modalità del puntatore. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) costruttore

Crea [SmartPtr](../) che punta all'oggetto specificato, o converte il puntatore grezzo in [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Oggetto puntato. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modalità del puntatore. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) costruttore

Copia costruisce l'oggetto [SmartPtr](../). Entrambi i puntatori puntano allo stesso oggetto successivamente.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Puntatore da copiare. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modalità del puntatore. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) costruttore

Copia costruisce l'oggetto [SmartPtr](../). Entrambi i puntatori puntano allo stesso oggetto successivamente. Esegue la conversione di tipo se consentita.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo dell'oggetto puntato da x. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Puntatore da copiare. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modalità del puntatore. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) costruttore

Spostamento costruisce l'oggetto [SmartPtr](../). In pratica, scambia due puntatori, se sono entrambi della stessa modalità. x può diventare inutilizzabile dopo la chiamata.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Puntatore da spostare. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modalità del puntatore. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) costruttore

Converte il tipo dell'array di riferimento creando un nuovo array di tipo diverso. Utile se in C# esiste un cast di tipo dell'array non supportato in C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Y | Tipo dell'array sorgente. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Puntatore all'array di cui creare una copia, ma con tipo di elementi diverso. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modalità del puntatore. |

## SmartPtr::SmartPtr(const Y&) costruttore

Inizializza un array vuoto. Usato per tradurre alcuni costrutti di codice C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| Y | Segnaposto del tipo EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) costruttore

Costruisce un [SmartPtr](../) che condivide le informazioni di proprietà con il valore iniziale di ptr, ma contiene un puntatore p non correlato e non gestito.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Un altro smart pointer da cui condividere la proprietà. |
| p | [Pointee_](../pointee_/) * | Puntatore a un oggetto da gestire. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modalità del puntatore. |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// Questa classe contiene un campo che verrà stampato.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Questa classe contiene un'istanza della classe Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Utilizzato per stampare una stringa dall'istanza della classe Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Stampa il numero di shared pointer che puntano all'oggetto.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Crea un SharedPtr a un'istanza della classe Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Crea un SharedPtr che punterà al campo dell'istanza della classe Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Imposta il puntatore 'bar' su nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data esiste ancora e il puntatore 'foo' è valido.
  PrintMessage(foo);

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
Numero di shared pointer: 1
Numero di shared pointer: 2
Numero di shared pointer: 0
Ciao, mondo!
*/
```

## Vedi anche

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)