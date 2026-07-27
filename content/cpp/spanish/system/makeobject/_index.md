---
title: MakeObject()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un objeto en el montón y devuelve un puntero compartido a él.
type: docs
weight: 2887
url: /es/system/makeobject/
---
## System::MakeObject(Args\&&...) función


Crea un objeto en el montón y devuelve un puntero compartido a él.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Clase a instanciar. |
| Args | Tipos de los argumentos del constructor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Argumentos del constructor. |

### Valor de retorno

[SmartPtr](../smartptr/) al nuevo objeto creado, siempre en modo compartido.

## System::MakeObject(Args\&&...) función


Crea un objeto en el montón y devuelve un puntero compartido a él.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [SmartPtr](../smartptr/) a clase a instanciar. |
| Args | Tipos de los argumentos del constructor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Argumentos del constructor. |

### Valor de retorno

[SmartPtr](../smartptr/) al nuevo objeto creado, siempre en modo compartido.

## Ver también

* Clase [SmartPtr](../smartptr/)
* Estructura [IsSmartPtr](../issmartptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)