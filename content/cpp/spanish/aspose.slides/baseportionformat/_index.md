---
title: BasePortionFormat
second_title: Referencia de API de Aspose.Slides para C++
description: Propiedades comunes de formato de porciones de texto.
type: docs
weight: 144
url: /es/aspose.slides/baseportionformat/
---
## BasePortionFormat clase


Common text portion formatting properties.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara con el objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Devuelve el Id de un idioma alternativo. Lea [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Devuelve la información de la fuente de script complejo. Null significa que la fuente no está definida y debe heredarse del Master. Lea [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Devuelve la información de la fuente de Asia Oriental. Null significa que la fuente no está definida y debe heredarse del Master. Lea [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Devuelve las propiedades de texto [EffectFormat](../effectformat/). No se aplica herencia. Solo lectura [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Devuelve el texto de superíndice o subíndice. Valor de -100 % (subíndice) a 100 % (superíndice). **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Lee **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Devuelve las propiedades de texto [FillFormat](../fillformat/). No se aplica herencia. Solo lectura [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Determina si la fuente es negrita. No se aplica herencia. Lee [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Devuelve la altura de la fuente de una porción. **std::numeric_limits<float>::quiet_NaN()** significa que la altura no está definida y debe heredarse del Master. Lee **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Determina si la fuente es cursiva. No se aplica herencia. Lee [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Devuelve el tipo de subrayado del texto. No se aplica herencia. Lee [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Devuelve el color usado para resaltar un texto. No se aplica herencia. Solo lectura [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Determina si el estilo de subrayado tiene sus propias propiedades [FillFormat](../fillformat/) o las hereda de las propiedades [FillFormat](../fillformat/) del texto. Lee [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Determina si el estilo de subrayado tiene sus propias propiedades [LineFormat](../lineformat/) o las hereda de las propiedades [LineFormat](../lineformat/) del texto. Lee [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Devuelve el tamaño de fuente mínimo para el cual se debe activar el kerning. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Lee **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Determina si los números deben ignorar el diseño vertical del texto específico de lenguas orientales. No se aplica herencia. Lee [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Devuelve el Id de un idioma de corrección. Usado para comprobar ortografía y gramática. Lea [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Devuelve la información de la fuente latina. Null significa que la fuente no está definida y debe heredarse del Master. Lea [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Devuelve las propiedades [LineFormat](../lineformat/) para el contorno de texto. No se aplica herencia. Solo lectura [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Determina si la altura del texto debe normalizarse. No se aplica herencia. Lee [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Devuelve el objeto Parent_Immediate. Solo lectura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Devuelve el padre [IPresentationComponent](../ipresentationcomponent/). Solo lectura [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Determina si el texto no debe ser corregido. No se aplica herencia. Lee [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Devuelve el incremento del espaciado entre caracteres. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Lee **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Obtiene un valor que indica si la verificación ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las comprobaciones ortográficas para los elementos de texto. Cuando se establece en true, la verificación ortográfica está permitida. El valor predeterminado es **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Devuelve el tipo de tachado de un texto. No se aplica herencia. Lee [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Devuelve la información de la fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Master. Lea [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Devuelve el tipo de capitalización del texto. No se aplica herencia. Lee [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Devuelve las propiedades de la línea de subrayado [FillFormat](../fillformat/). No se aplica herencia. Solo lectura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Devuelve las propiedades [LineFormat](../lineformat/) usadas para delinear la línea de subrayado. No se aplica herencia. Solo lectura [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Devuelve el código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Establece el Id de un idioma alternativo. Escriba [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Establece la información de la fuente de script complejo. Null significa que la fuente no está definida y debe heredarse del Master. Escriba [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Establece la información de la fuente de Asia Oriental. Null significa que la fuente no está definida y debe heredarse del Master. Escriba [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Establece el texto de superíndice o subíndice. Valor de -100 % (subíndice) a 100 % (superíndice). **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Escriba **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Determina si la fuente es negrita. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Establece la altura de la fuente de una porción. **std::numeric_limits<float>::quiet_NaN()** significa que la altura no está definida y debe heredarse del Master. Escriba **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Determina si la fuente es cursiva. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Establece el tipo de subrayado del texto. No se aplica herencia. Escriba [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Determina si el estilo de subrayado tiene sus propias propiedades [FillFormat](../fillformat/) o las hereda de las propiedades [FillFormat](../fillformat/) del texto. Escriba [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Determina si el estilo de subrayado tiene sus propias propiedades [LineFormat](../lineformat/) o las hereda de las propiedades [LineFormat](../lineformat/) del texto. Escriba [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Establece el tamaño de fuente mínimo para el cual se debe activar el kerning. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Escriba **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Determina si los números deben ignorar el diseño vertical del texto específico de lenguas orientales. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Establece el Id de un idioma de corrección. Usado para comprobar ortografía y gramática. Escriba [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Establece la información de la fuente latina. Null significa que la fuente no está definida y debe heredarse del Master. Escriba [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Determina si la altura del texto debe normalizarse. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Determina si el texto no debe ser corregido. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Establece el incremento del espaciado entre caracteres. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Escriba **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Establece un valor que indica si la verificación ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las comprobaciones ortográficas para los elementos de texto. Cuando se establece en true, la verificación ortográfica está permitida. El valor predeterminado es **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Establece el tipo de tachado de un texto. No se aplica herencia. Escriba [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Establece la información de la fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Master. Escriba [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Establece el tipo de capitalización del texto. No se aplica herencia. Escriba [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras internas. |

## Ver también

* Clase [PVIObject](../pviobject/)
* Clase [IBasePortionFormat](../ibaseportionformat/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)