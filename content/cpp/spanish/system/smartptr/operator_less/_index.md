---
title: operator<()
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona semántica de comparación menor para la clase SmartPtr.
type: docs
weight: 235
url: /es/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const método

Proporciona semántica de comparación menor para la clase [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Y | Tipo de puntero a comparar con el actual. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | Y * | Puntero a comparar con el actual. |

### Valor de retorno

True si el objeto referenciado por [SmartPtr](../) es 'menor' que p y false en caso contrario.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const método

Proporciona semántica de comparación menor para la clase [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Y | Tipo de puntero a comparar con el actual. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Puntero a comparar con el actual. |

### Valor de retorno

True si el objeto referenciado por [SmartPtr](../) es 'menor' que x y false en caso contrario.

## Ver también

* Clase [SmartPtr](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)