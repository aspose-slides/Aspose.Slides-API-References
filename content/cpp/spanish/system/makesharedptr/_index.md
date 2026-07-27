---
title: MakeSharedPtr()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte un puntero crudo en un puntero inteligente.
type: docs
weight: 2900
url: /es/system/makesharedptr/
---
## System::MakeSharedPtr(X *) función

Convierte un puntero crudo a un puntero inteligente.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del objeto apuntado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | X * | Puntero crudo al objeto. |

### Valor de retorno

Puntero inteligente compartido al objeto.

## System::MakeSharedPtr(const X *) función

Convierte un puntero crudo a un puntero inteligente. Sobrecarga para punteros const. Útil, por ejemplo, al usar la variable 'this' en métodos de C# traducidos como const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del objeto apuntado. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | const X * | Puntero crudo al objeto. |

### Valor de retorno

Puntero inteligente compartido al objeto.

## Véase también

* Clase [SmartPtr](../smartptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)