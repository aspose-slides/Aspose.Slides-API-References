---
title: SmartPtr()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un objeto SmartPtr del modo requerido.
type: docs
weight: 1
url: /es/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) constructor

Crea el objeto [SmartPtr](../) del modo requerido.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo del puntero. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor

Crea un objeto [SmartPtr](../) de puntero nulo del modo requerido.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | std::nullptr_t | Modo del puntero. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor

Crea [SmartPtr](../) que apunta al objeto especificado, o convierte un puntero crudo a [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Objeto apuntado. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo del puntero. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) constructor

Construye una copia del objeto [SmartPtr](../). Ambos punteros apuntan al mismo objeto después.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Puntero a copiar. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo del puntero. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor

Construye una copia del objeto [SmartPtr](../). Ambos punteros apuntan al mismo objeto después. Realiza conversión de tipo si está permitido.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo del objeto señalado por x. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Puntero a copiar. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo del puntero. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) constructor

Construye el objeto [SmartPtr](../) mediante movimiento. Efectivamente, intercambia dos punteros, si ambos son del mismo modo. x puede quedar inutilizable después de la llamada.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Puntero a mover. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo del puntero. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor

Convierte el tipo del array referenciado creando un nuevo array de tipo diferente. Útil si en C# existe una conversión de tipo de array que no está soportada en C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Y | Tipo del array origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Puntero al array del que crear una copia, pero con un tipo de elementos diferente. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo del puntero. |

## SmartPtr::SmartPtr(const Y\&) constructor

Inicializa un array vacío. Utilizado para traducir algunas construcciones de código C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Y | Marcador de posición del tipo EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor

Construye un [SmartPtr](../) que comparte la información de propiedad con el valor inicial de ptr, pero mantiene un puntero no relacionado y no administrado p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Otro puntero inteligente para compartir la propiedad con la del origen. |
| p | [Pointee_](../pointee_/) * | Puntero al objeto a gestionar. |
| mode | [SmartPtrMode](../../smartptrmode/) | Modo del puntero. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// Esta clase contiene un campo que será impreso.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Esta clase contiene una instancia de la clase Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Utilizado para imprimir una cadena desde la instancia de la clase Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Imprime la cantidad de punteros compartidos que apuntan al objeto.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Crear SharedPtr a una instancia de la clase Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Crear SharedPtr que apuntará al campo de la instancia de la clase Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Hacer que el puntero 'bar' apunte a nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data aún existe y el puntero 'foo' es válido.
  PrintMessage(foo);

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## Ver también

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Clase [SmartPtr](../)
* Clase [Array](../../array/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)