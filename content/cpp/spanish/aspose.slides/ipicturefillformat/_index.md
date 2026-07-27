---
title: IPictureFillFormat
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un estilo de relleno de imagen.
type: docs
weight: 3225
url: /es/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat clase


Representa un estilo de relleno de imagen.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Elimina áreas recortadas del relleno [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Devuelve el número de por ciento de la altura real de la imagen que se recorta en la parte inferior de la picture. Solo lectura **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Devuelve el número de por ciento de la anchura real de la imagen que se recorta en el lado izquierdo de la picture. Solo lectura **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Devuelve el número de por ciento de la anchura real de la imagen que se recorta en el lado derecho de la picture. Solo lectura **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Devuelve el número de por ciento de la altura real de la imagen que se recorta en la parte superior de la picture. Solo lectura **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Devuelve los dpi que se utilizan para rellenar una picture. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Devuelve la picture. Solo lectura [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Devuelve el modo de relleno de picture. Solo [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Devuelve el borde inferior del rectángulo de relleno definido por un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. Un porcentaje positivo indica un inset, mientras que un porcentaje negativo indica un outset. Solo lectura **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Devuelve el borde izquierdo del rectángulo de relleno definido por un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. Un porcentaje positivo indica un inset, mientras que un porcentaje negativo indica un outset. Solo lectura **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Devuelve el borde derecho del rectángulo de relleno definido por un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo indica un inset, mientras que un porcentaje negativo indica un outset. Solo lectura **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Devuelve el borde superior del rectángulo de relleno definido por un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. Un porcentaje positivo indica un inset, mientras que un porcentaje negativo indica un outset. Solo lectura **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Devuelve cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite en la forma. Solo [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Gira el mosaico de textura alrededor de su eje horizontal, vertical o ambos. Solo [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Devuelve el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Solo lectura **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Devuelve el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Solo lectura **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Devuelve la escala horizontal del relleno de textura como un porcentaje. Solo lectura **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Devuelve la escala vertical del relleno de textura como un porcentaje. Solo lectura **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa la instrucción C# lock() bloqueando. Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de string y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Establece el número de por ciento de la altura real de la imagen que se recorta en la parte inferior de la picture. Escribe **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Establece el número de por ciento de la anchura real de la imagen que se recorta en el lado izquierdo de la picture. Escribe **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Establece el número de por ciento de la anchura real de la imagen que se recorta en el lado derecho de la picture. Escribe **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Establece el número de por ciento de la altura real de la imagen que se recorta en la parte superior de la picture. Escribe **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Establece los dpi que se usan para rellenar una picture. Escribe **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Establece el modo de relleno de picture. Escribe [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Establece el borde inferior del rectángulo de relleno definido por un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. Un porcentaje positivo indica un inset, mientras que un porcentaje negativo indica un outset. Escribe **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Establece el borde izquierdo del rectángulo de relleno definido por un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. Un porcentaje positivo indica un inset, mientras que un porcentaje negativo indica un outset. Escribe **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Establece el borde derecho del rectángulo de relleno definido por un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo indica un inset, mientras que un porcentaje negativo indica un outset. Escribe **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Establece el borde superior del rectángulo de relleno definido por un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. Un porcentaje positivo indica un inset, mientras que un porcentaje negativo indica un outset. Escribe **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite en la forma. Escribe [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Gira el mosaico de textura alrededor de su eje horizontal, vertical o ambos. Escribe [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Escribe **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Escribe **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Establece la escala horizontal del relleno de textura como un porcentaje. Escribe **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Establece la escala vertical del relleno de textura como un porcentaje. Escribe **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa la instrucción C# lock() desbloqueando. Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Ver también

* Clase [IFillParamSource](../ifillparamsource/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)