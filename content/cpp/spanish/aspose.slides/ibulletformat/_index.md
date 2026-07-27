---
title: IBulletFormat
second_title: Referencia de API de Aspose.Slides para C++
description: Representa las propiedades de formato de viñetas de párrafo.
type: docs
weight: 1561
url: /es/aspose.slides/ibulletformat/
---
## IBulletFormat clase

Representa las propiedades de formato de viñetas de párrafo.

```cpp
class IBulletFormat : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | Establece desplazamientos predeterminados distintos de cero para el sangrado efectivo del párrafo Indent y MarginLeft cuando las viñetas están habilitadas (como hace PowerPoint si se habilitan viñetas/numeración en el párrafo). Si las viñetas están deshabilitadas, simplemente restablece Indent y MarginLeft del párrafo (como hace PowerPoint si se deshabilitan viñetas/numeración en el párrafo). Los desplazamientos de sangrado se aplican respecto al contexto actual de la viñeta - IBulletFormat::get(set)_Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos distintos de cero se aplican al Indent y MarginLeft efectivos del párrafo actual (haciendo que los valores resultantes sean valores locales). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual char16_t [get_Char](./get_char/)() | Devuelve el carácter de viñeta de un párrafo sin herencia. Leer **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | Devuelve el formato de color de una viñeta de un párrafo sin herencia. Sólo lectura [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | Devuelve la fuente de la viñeta de un párrafo sin herencia. Leer [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | Devuelve la altura de la viñeta de un párrafo sin herencia. El valor std::numeric_limits<float>::quiet_NaN() determina que la viñeta hereda la altura de la primera porción del párrafo. Leer **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. **[NullableBool::True](../nullablebool/)** si la viñeta tiene color propio y **[NullableBool::False](../nullablebool/)** si la viñeta hereda el color de la primera porción del párrafo. Leer [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. **[NullableBool::True](../nullablebool/)** si la viñeta tiene fuente propia y **[NullableBool::False](../nullablebool/)** si la viñeta hereda la fuente de la primera porción del párrafo. Leer [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | Devuelve el primer número que se usa para el grupo de viñetas numeradas sin herencia. Leer **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | Devuelve el estilo de una viñeta numerada sin herencia. Leer [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Devuelve la imagen usada como viñeta en un párrafo sin herencia. Sólo lectura [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | Devuelve el tipo de viñeta de un párrafo sin herencia. Leer [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtiene los datos de formato efectivo de la viñeta con la herencia aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_Char](./set_char/)(char16_t) | Establece el carácter de viñeta de un párrafo sin herencia. Escribir **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Establece la fuente de la viñeta de un párrafo sin herencia. Escribir [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | Establece la altura de la viñeta de un párrafo sin herencia. El valor std::numeric_limits<float>::quiet_NaN() determina que la viñeta hereda la altura de la primera porción del párrafo. Escribir **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. **[NullableBool::True](../nullablebool/)** si la viñeta tiene color propio y **[NullableBool::False](../nullablebool/)** si la viñeta hereda el color de la primera porción del párrafo. Escribir [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. **[NullableBool::True](../nullablebool/)** si la viñeta tiene fuente propia y **[NullableBool::False](../nullablebool/)** si la viñeta hereda la fuente de la primera porción del párrafo. Escribir [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | Establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. Escribir **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | Establece el estilo de una viñeta numerada sin herencia. Escribir [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | Establece el tipo de viñeta de un párrafo sin herencia. Escribir [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)