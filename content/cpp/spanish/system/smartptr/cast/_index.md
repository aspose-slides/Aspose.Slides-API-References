---
title: Cast()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el puntero a su propio tipo.
type: docs
weight: 287
url: /es/system/smartptr/cast/
---
## SmartPtr::Cast() const método

Convierte el puntero a su propio tipo.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Y | Tipo objetivo del objeto apuntado. |
| Check | Indicadores para lanzar excepción si no hay conversión disponible. |

### Valor de retorno

Puntero del tipo cambiado que siempre está en modo compartido.

## SmartPtr::Cast() const método

Convierte el puntero al tipo base usando static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Y | Tipo objetivo del objeto apuntado. |
| Check | Indicadores para lanzar excepción si no hay conversión disponible. |

### Valor de retorno

Puntero del tipo cambiado que siempre está en modo compartido.

## SmartPtr::Cast() const método

Convierte el puntero al tipo derivado usando dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Y | Tipo objetivo del objeto apuntado. |
| Check | Indicadores para lanzar excepción si no hay conversión disponible. |

### Valor de retorno

Puntero del tipo cambiado que siempre está en modo compartido. Lanza InvalidCastException si no hay conversión disponible.

## SmartPtr::Cast() const método

Convierte el puntero al tipo derivado usando dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Y | Tipo objetivo del objeto apuntado. |
| Check | Indicadores para lanzar excepción si no hay conversión disponible. |

### Valor de retorno

Puntero del tipo cambiado que siempre está en modo compartido. Devuelve nullptr si no hay conversión disponible.

## Ver también

* Clase [SmartPtr](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)