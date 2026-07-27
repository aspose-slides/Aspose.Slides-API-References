---
title: setter_increment_wrap()
second_title: Referencia de la API de Aspose.Slides para C++
description: El traductor traduce las expresiones de incremento de C# dirigidas a la propiedad de una clase que tiene setter y getter definidos, en una invocación de esta función.
type: docs
weight: 2835
url: /es/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) función

El traductor traduce las expresiones de incremento de C# dirigidas a la propiedad de una clase que tiene setter y getter definidos, en una invocación de esta función.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pGetter | T(*)() | Puntero a función que apunta a la función libre getter de la propiedad |
| pSetter | void(*)(T) | Puntero a función que apunta a la función libre setter de la propiedad |

### Valor de retorno

El valor incrementado de la propiedad

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) función

El traductor traduce las expresiones de incremento de C# dirigidas a la propiedad de una clase que tiene setter y getter definidos, en una invocación de esta función.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad |
| Host | - clase de la instancia a modificar |
| HostGet | - Host mismo, o su tipo base, donde se define el getter de la propiedad |
| HostSet | - Host mismo, o su tipo base, donde se define el setter de la propiedad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | Un puntero a un objeto cuya propiedad será incrementada |
| pGetter | T(HostGet::*)() | Puntero a función que apunta al método getter de la propiedad |
| pSetter | void(HostSet::*)(T) | Puntero a función que apunta al método setter de la propiedad |

### Valor de retorno

El valor incrementado de la propiedad

## Véase también

* Namespace [System](../)
* Library [Aspose.Slides](../../)