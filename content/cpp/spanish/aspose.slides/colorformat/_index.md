---
title: ColorFormat
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un color utilizado en una presentación.
type: docs
weight: 339
url: /es/aspose.slides/colorformat/
---
## ColorFormat clase

Representa un color utilizado en una presentación.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Copia el formato de color de "color". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Comprueba la igualdad con el objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **uint8_t** [get_B](./get_b/)() override | Devuelve el componente azul de un color. Todas las transformaciones de color se ignoran. Lee **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Devuelve el color resultante (con todas las transformaciones de color aplicadas). Establece los colores RGB y borra todas las transformaciones de color. Lee [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Devuelve la operación de transformación de color aplicada al color en el índice especificado. Lectura/escritura [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Devuelve la colección de transformaciones de color aplicadas a un color. Solo lectura [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Devuelve el método de definición del color. Lee [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Devuelve el componente azul de un color. Todas las transformaciones de color se ignoran. Lee **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Devuelve el componente verde de un color. Todas las transformaciones de color se ignoran. Lee **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Devuelve el componente rojo de un color. Todas las transformaciones de color se ignoran. Lee **float**. |
| **uint8_t** [get_G](./get_g/)() override | Devuelve el componente verde de un color. Todas las transformaciones de color se ignoran. |
| **float** [get_Hue](./get_hue/)() override | Devuelve el componente matiz de un color en representación HSL. Todas las transformaciones de color se ignoran. Lee **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Devuelve el componente luminancia de un color en representación HSL. Todas las transformaciones de color se ignoran. Lee **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Devuelve el objeto Parent_Immediate. Solo lectura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Devuelve el padre [IPresentationComponent](../ipresentationcomponent/). Solo lectura [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Devuelve el preset de color. Lee [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Devuelve el componente rojo de un color. Todas las transformaciones de color se ignoran. Lee **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Devuelve el componente saturación de un color en representación HSL. Todas las transformaciones de color se ignoran. Lee **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Devuelve el color identificado por un esquema de color. Lee [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Devuelve el color identificado por la tabla de colores del sistema. Lee [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Devuelve el código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de constructores en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de constructores en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_B](./set_b/)(**uint8_t**) override | Establece el componente azul de un color. Todas las transformaciones de color se ignoran. Escritura **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Devuelve el color resultante (con todas las transformaciones de color aplicadas). Establece los colores RGB y borra todas las transformaciones de color. Escritura [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Establece la operación de transformación de color aplicada al color en el índice especificado. Lectura/escritura [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Establece el método de definición del color. Escritura [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Establece el componente azul de un color. Todas las transformaciones de color se ignoran. Escritura **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Establece el componente verde de un color. Todas las transformaciones de color se ignoran. Escritura **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Establece el componente rojo de un color. Todas las transformaciones de color se ignoran. Escritura **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Establece el componente verde de un color. Todas las transformaciones de color se ignoran. |
| void [set_Hue](./set_hue/)(**float**) override | Establece el componente matiz de un color en representación HSL. Todas las transformaciones de color se ignoran. Escritura **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Establece el componente luminancia de un color en representación HSL. Todas las transformaciones de color se ignoran. Escritura **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Establece el preset de color. Escritura [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Establece el componente rojo de un color. Todas las transformaciones de color se ignoran. Escritura **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Establece el componente saturación de un color en representación HSL. Todas las transformaciones de color se ignoran. Escritura **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Establece el color identificado por un esquema de color. Escritura [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Establece el color identificado por la tabla de colores del sistema. Escritura [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Devuelve un [System::String](../../system/string/) que representa el formato de color actual. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [PVIObject](../pviobject/)
* Clase [IColorFormat](../icolorformat/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)