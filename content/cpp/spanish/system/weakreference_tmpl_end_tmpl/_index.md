---
title: WeakReference<>
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa una referencia débil, que referencia un objeto mientras aún permite que ese objeto sea eliminado.
type: docs
weight: 1522
url: /es/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> clase

Representa una referencia débil, que referencia un objeto mientras aún permite que ese objeto sea eliminado.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Obtiene una indicación de si el objeto referenciado por el actual objeto WeakReference ha sido eliminado. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Obtiene el objeto (el objetivo) referenciado por el actual objeto WeakReference. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Establece el objeto (el objetivo) referenciado por el actual objeto WeakReference. |
| [WeakReference](./weakreference/)() | Constructor predeterminado. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Constructor a partir de nullptr. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Inicializa una nueva instancia de la clase WeakReference, referenciando el objeto especificado. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Inicializa una nueva instancia de la clase WeakReference, referenciando el objeto especificado. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)