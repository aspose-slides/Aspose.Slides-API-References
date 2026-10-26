---
title: PictureFillFormat
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un estilo de relleno de imagen.
type: docs
weight: 4720
url: /es/aspose.slides/picturefillformat/
---
## PictureFillFormat clase

Representa un estilo de relleno de imagen.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Elimina las áreas recortadas del relleno [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara con el objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Devuelve el número de porcentaje de la altura real de la imagen que se recorta en la parte inferior de la imagen. Lee **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Devuelve el número de porcentaje del ancho real de la imagen que se recorta en el lado izquierdo de la imagen. Lee **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Devuelve el número de porcentaje del ancho real de la imagen que se recorta en el lado derecho de la imagen. Lee **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Devuelve el número de porcentaje de la altura real de la imagen que se recorta en la parte superior de la imagen. Lee **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Devuelve los ppp (dpi) que se usan para rellenar una imagen. Lee **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Devuelve el objeto Parent_Immediate. Solo lectura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Devuelve el padre [IPresentationComponent](../ipresentationcomponent/). Solo lectura [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Devuelve la imagen. Solo lectura [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Devuelve el modo de relleno de imagen. Lee [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Devuelve el borde inferior del rectángulo de relleno que está definido por un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una expansión. Lee **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Devuelve el borde izquierdo del rectángulo de relleno que está definido por un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una expansión. Lee **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Devuelve el borde derecho del rectángulo de relleno que está definido por un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una expansión. Lee **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Devuelve el borde superior del rectángulo de relleno que está definido por un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una expansión. Lee **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Devuelve cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite a lo largo de la forma. Lee [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Voltea el mosaico de textura alrededor de su eje horizontal, vertical o ambos. Lee [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Devuelve el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Lee **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Devuelve el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Lee **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Devuelve la escala horizontal del relleno de textura como un porcentaje. Lee **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Devuelve la escala vertical del relleno de textura como un porcentaje. Lee **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociado al objeto. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Devuelve el código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas por el valor especificado. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Define el número de porcentaje de la altura real de la imagen que se recorta en la parte inferior de la imagen. Escribe **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Define el número de porcentaje del ancho real de la imagen que se recorta en el lado izquierdo de la imagen. Escribe **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Define el número de porcentaje del ancho real de la imagen que se recorta en el lado derecho de la imagen. Escribe **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Define el número de porcentaje de la altura real de la imagen que se recorta en la parte superior de la imagen. Escribe **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Define los ppp (dpi) que se usan para rellenar una imagen. Escribe **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Define el modo de relleno de imagen. Escribe [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Define el borde inferior del rectángulo de relleno que está definido por un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una expansión. Escribe **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Define el borde izquierdo del rectángulo de relleno que está definido por un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una expansión. Escribe **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Define el borde derecho del rectángulo de relleno que está definido por un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una expansión. Escribe **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Define el borde superior del rectángulo de relleno que está definido por un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. Un porcentaje positivo especifica una inserción, mientras que un porcentaje negativo especifica una expansión. Escribe **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Define cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite a lo largo de la forma. Escribe [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Voltea el mosaico de textura alrededor de su eje horizontal, vertical o ambos. Escribe [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Define el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Escribe **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Define el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Escribe **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Define la escala horizontal del relleno de textura como un porcentaje. Escribe **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Define la escala vertical del relleno de textura como un porcentaje. Escribe **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [PVIObject](../pviobject/)
* Clase [IPictureFillFormat](../ipicturefillformat/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)