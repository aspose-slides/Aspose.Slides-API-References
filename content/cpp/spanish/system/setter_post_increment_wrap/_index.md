---
title: setter_post_increment_wrap()
second_title: Referencia de la API de Aspose.Slides para C++
description: El traductor traduce las expresiones de post-incremento de C# que apuntan a la propiedad de una clase que tiene definido setter y getter, en una invocación de esta función.
type: docs
weight: 2848
url: /es/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) función

El traductor traduce expresiones de post-incremento de C# que apuntan a la propiedad de una clase que tiene definido setter y getter, en una invocación de esta función.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
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

### Valor devuelto

El valor de la propiedad antes de incrementarse

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) función

El traductor traduce expresiones de post-incremento de C# que apuntan a la propiedad de una instancia que tiene definido setter y getter, en una invocación de esta función (sobrecarga para getter no const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad. |
| Host | - clase de la instancia a modificar |
| HostGet | - Host mismo, o su tipo base, donde se define el getter de la propiedad |
| HostSet | - Host mismo, o su tipo base, donde se define el setter de la propiedad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | Instancia para la que se llaman los getters y setters. |
| pGetter | T(HostGet::*)() | Puntero a función que apunta a la función getter de la propiedad |
| pSetter | void(HostSet::*)(T) | Puntero a función que apunta a la función setter de la propiedad |

### Valor devuelto

El valor de la propiedad antes de incrementarse

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) función

El traductor traduce expresiones de post-incremento de C# que apuntan a la propiedad de una instancia que tiene definido setter y getter, en una invocación de esta función (sobrecarga para getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad. |
| Host | - clase de la instancia a modificar |
| HostConstGet | - Host mismo, o su tipo base, donde se define el getter de la propiedad |
| HostSet | - Host mismo, o su tipo base, donde se define el setter de la propiedad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | Instancia para la que se llaman los getters y setters. |
| pGetter | T(HostConstGet::*)() const | Puntero a función que apunta a la función getter de la propiedad |
| pSetter | void(HostSet::*)(T) | Puntero a función que apunta a la función setter de la propiedad |

### Valor devuelto

El valor de la propiedad antes de incrementarse

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)