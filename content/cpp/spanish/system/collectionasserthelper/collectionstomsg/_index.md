---
title: CollectionsToMsg()
second_title: Referencia de la API de Aspose.Slides para C++
description: Serializa dos colecciones para su representación en el mensaje.
type: docs
weight: 53
url: /es/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method

Serializa dos colecciones para su representación en el mensaje.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T1 | Tipo de elemento esperado de la colección. |
| T2 | Tipo de elemento real de la colección. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Una cadena personalizada que se inserta antes del valor esperado en el mensaje resultante |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Colección esperada. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Colección real. |

### Valor devuelto

Mensaje fácil de leer sobre el contenido de las colecciones.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Estructura [CollectionAssertHelper](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)