---
title: setter_wrap()
second_title: Referencia de API de Aspose.Slides para C++
description: Sobrecarga para funciones setter estáticas con conversión de tipo.
type: docs
weight: 2822
url: /es/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) función

Sobrecarga para funciones setter estáticas con conversión de tipo.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor. |
| T2 | Tipo esperado por la función setter. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pSetter | void(*)(T2) | Referencia a la función setter estática. |
| value | T | Valor a establecer. |

### Valor devuelto

establece el valor.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) función

Sobrecarga para funciones setter de instancia con conversión de tipo.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor. |
| T2 | Tipo esperado por la función setter. |
| Host | Tipo de instancia. |
| HostSet | - Host mismo, o su tipo base, donde se define el setter de la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | [Object](../object/) para llamar a la función setter. |
| pSetter | void(HostSet::*)(T2) | Referencia a la función setter. |
| value | T | Valor a establecer. |

### Valor devuelto

establece el valor.

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)