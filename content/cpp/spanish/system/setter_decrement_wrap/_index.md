---
title: setter_decrement_wrap()
second_title: Referencia de API de Aspose.Slides para C++
description: El traductor traduce las expresiones de predecremento de C# que apuntan a la propiedad de una clase que tiene setter y getter definidos, en la invocación de esta función.
type: docs
weight: 2861
url: /es/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) función

El traductor traduce las expresiones de predecremento de C# dirigidas a la propiedad de una clase que tiene setter y getter definidos, en la invocación de esta función.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of the property |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pGetter | T(*)() | Function pointer pointing to the property's getter free function |
| pSetter | void(*)(T) | Function pointer pointing to the property's setter free function |

### Valor devuelto

El valor de la propiedad antes de incrementarse

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) función

El traductor traduce las expresiones de predecremento de C# dirigidas a la propiedad de una instancia que tiene setter y getter definidos, en la invocación de esta función (sobrecarga para getter no const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of the property. |
| Host | - clase de la instancia a modificar |
| HostGet | - Host mismo, o su tipo base, donde se define el getter de la propiedad |
| HostSet | - Host mismo, o su tipo base, donde se define el setter de la propiedad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | Instance to call getters and setters for. |
| pGetter | T(HostGet::*)() | Function pointer pointing to the property's getter function |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter function |

### Valor devuelto

El valor de la propiedad antes de incrementarse

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) función

El traductor traduce las expresiones de predecremento de C# dirigidas a la propiedad de una instancia que tiene setter y getter definidos, en la invocación de esta función (sobrecarga para getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of the property. |
| Host | - clase de la instancia a modificar |
| HostConstGet | - Host mismo, o su tipo base, donde se define el getter de la propiedad |
| HostSet | - Host mismo, o su tipo base, donde se define el setter de la propiedad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | Instance to call getters and setters for. |
| pGetter | T(HostConstGet::*)() const | Function pointer pointing to the property's getter function |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter function |

### Valor devuelto

El valor de la propiedad antes de incrementarse

## Ver también

* Namespace [System](../)
* Library [Aspose.Slides](../../)