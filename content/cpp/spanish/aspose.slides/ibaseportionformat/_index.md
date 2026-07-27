---
title: IBasePortionFormat
second_title: Referencia de la API de Aspose.Slides para C++
description: Esta clase contiene las propiedades de formato de porción de texto. A diferencia de IPortionFormatEffectiveData, todas las propiedades de esta clase son modificables.
type: docs
weight: 1457
url: /es/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat clase


Esta clase contiene las propiedades de formato de porción de texto. A diferencia de [IPortionFormatEffectiveData](../iportionformateffectivedata/), todas las propiedades de esta clase son modificables.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Devuelve el Id de un lenguaje alternativo. Leer [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Devuelve la información de fuente de script complejo. Null significa que la fuente no está definida y debe heredarse del Maestro. Leer [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Devuelve la información de fuente de Asia Oriental. Null significa que la fuente no está definida y debe heredarse del Maestro. Leer [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Devuelve las propiedades de texto [EffectFormat](../effectformat/). No se aplica herencia. Solo lectura [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Devuelve el texto en superíndice o subíndice. Valor entre -100 % (subíndice) y 100 % (superíndice). **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Maestro. Leer **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Devuelve las propiedades de texto [FillFormat](../fillformat/). No se aplica herencia. Solo lectura [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Determina si la fuente es negrita. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Devuelve la altura de fuente de una porción. **std::numeric_limits<float>::quiet_NaN()** significa que la altura no está definida y debe heredarse del Maestro. Leer **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Determina si la fuente es cursiva. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Devuelve el tipo de subrayado de texto. No se aplica herencia. Leer [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Devuelve el color usado para resaltar un texto. No se aplica herencia. Solo lectura [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Determina si el estilo de subrayado tiene sus propias propiedades [FillFormat](../fillformat/) o las hereda de las propiedades [FillFormat](../fillformat/) del texto. Leer [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Determina si el estilo de subrayado tiene sus propias propiedades [LineFormat](../lineformat/) o las hereda de las propiedades [LineFormat](../lineformat/) del texto. Leer [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Devuelve el tamaño de fuente mínimo para el que debe activarse el kerning. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Maestro. Leer **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Devuelve el Id de un lenguaje de revisión. Se usa para comprobar ortografía y gramática. Leer [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Devuelve la información de fuente latina. Null significa que la fuente no está definida y debe heredarse del Maestro. Leer [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Devuelve las propiedades [LineFormat](../lineformat/) para el contorno de texto. No se aplica herencia. Solo lectura [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Determina si la altura de un texto debe normalizarse. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Determina si el texto no debe revisarse. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Devuelve el incremento de espaciado entre caracteres. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Maestro. Leer **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Obtiene un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Devuelve el tipo de tachado de un texto. No se aplica herencia. Leer [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Devuelve la información de fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Maestro. Leer [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Devuelve el tipo de capitalización del texto. No se aplica herencia. Leer [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Devuelve las propiedades de la línea de subrayado [FillFormat](../fillformat/). No se aplica herencia. Solo lectura [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Devuelve las propiedades [LineFormat](../lineformat/) usadas para contornear la línea de subrayado. No se aplica herencia. Solo lectura [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y habilita la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y habilita la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Establece el Id de un lenguaje alternativo. Escriba [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Establece la información de fuente de script complejo. Null significa que la fuente no está definida y debe heredarse del Maestro. Escriba [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Establece la información de fuente de Asia Oriental. Null significa que la fuente no está definida y debe heredarse del Maestro. Escriba [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Establece el texto en superíndice o subíndice. Valor entre -100 % (subíndice) y 100 % (superíndice). **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Maestro. Escriba **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Determina si la fuente es negrita. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Establece la altura de fuente de una porción. **std::numeric_limits<float>::quiet_NaN()** significa que la altura no está definida y debe heredarse del Maestro. Escriba **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Determina si la fuente es cursiva. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Establece el tipo de subrayado de texto. No se aplica herencia. Escriba [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Determina si el estilo de subrayado tiene sus propias propiedades [FillFormat](../fillformat/) o las hereda de las propiedades [FillFormat](../fillformat/) del texto. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Determina si el estilo de subrayado tiene sus propias propiedades [LineFormat](../lineformat/) o las hereda de las propiedades [LineFormat](../lineformat/) del texto. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Establece el tamaño de fuente mínimo, para el cual debe activarse el kerning. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Maestro. Escriba **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Establece el Id de un lenguaje de revisión. Se usa para comprobar ortografía y gramática. Escriba [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Establece la información de fuente latina. Null significa que la fuente no está definida y debe heredarse del Maestro. Escriba [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Determina si la altura de un texto debe normalizarse. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Determina si el texto no debe revisarse. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Establece el incremento de espaciado entre caracteres. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Maestro. Escriba **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, se permite la corrección ortográfica. El valor predeterminado es **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Establece el tipo de tachado de un texto. No se aplica herencia. Escriba [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Establece la información de fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Maestro. Escriba [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Establece el tipo de capitalización del texto. No se aplica herencia. Escriba [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Comentarios


Esta clase se utiliza para obtener y manipular las propiedades de formato de porción de texto definidas para la porción específica. Esto significa que no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores efectivos de los parámetros de formato, incluidas las heredadas, necesita usar el método [IPortionFormat::GetEffective](../iportionformat/geteffective/) que devuelve una instancia [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)