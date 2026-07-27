---
title: PPImage
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa una imagen en una presentación.
type: docs
weight: 4824
url: /es/aspose.slides/ppimage/
---
## PPImage clase

Representa una imagen en una presentación.

```cpp
class PPImage : public Aspose::Slides::IPPImage,
                public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [Dispose](./dispose/)() override | Elimina el objeto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_BinaryData](./get_binarydata/)() override | Devuelve una copia de los datos de una imagen. Solo lectura **uint8_t**[]. |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Devuelve un tipo MIME de una imagen, codificado en [PPImage::get_BinaryData](./get_binarydata/). Solo lectura [System::String](../../system/string/). |
| **int32_t** [get_Height](./get_height/)() override | Devuelve una altura de una imagen. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IImage](../iimage/)\> [get_Image](./get_image/)() override | Devuelve una copia de una imagen. Solo lectura [IImage](../iimage/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::ISvgImage](../isvgimage/)\> [get_SvgImage](./get_svgimage/)() const override | Devuelve el objeto [ISvgImage](../isvgimage/) [ISvgImage](../isvgimage/) |
| **int32_t** [get_Width](./get_width/)() override | Devuelve una anchura de una imagen. Solo lectura **int32_t**. |
| **int32_t** [get_X](./get_x/)() override | Devuelve una compensación X de una imagen. Solo lectura **int32_t**. |
| **int32_t** [get_Y](./get_y/)() override | Devuelve una compensación Y de una imagen. Solo lectura **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de una imagen. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia el objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [ReplaceImage](./replaceimage/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Reemplaza los datos de la imagen. |
| void [ReplaceImage](./replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IImage](../iimage/)\>) override | Reemplaza los datos de la imagen. Atención: cuando Image es metafile, se rasterizará. Use ReplaceImage(byte[]) en su lugar |
| void [ReplaceImage](./replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IPPImage](../ippimage/)\>) override | Reemplaza los datos de la imagen. |
| virtual void [ReplaceImage](../ippimage/replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>) | Reemplaza la imagen. |
| virtual void [ReplaceImage](../ippimage/replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Reemplaza la imagen. |
| void [set_SvgImage](./set_svgimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::ISvgImage](../isvgimage/)\>) override | Establece el objeto [ISvgImage](../isvgimage/) [ISvgImage](../isvgimage/) |
| virtual void [set_SvgImage](../ippimage/set_svgimage/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgImage](../isvgimage/)\>) | Establece el objeto [ISvgImage](../isvgimage/) [ISvgImage](../isvgimage/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IPPImage](../ippimage/)
* Clase [IDisposable](../../system/idisposable/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)