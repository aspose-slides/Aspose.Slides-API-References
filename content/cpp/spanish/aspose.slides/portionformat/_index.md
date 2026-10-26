---
title: PortionFormat
second_title: Referencia de API de Aspose.Slides para C++
description: Esta clase contiene las propiedades de formato de porción de texto. A diferencia de IPortionFormatEffectiveData, todas las propiedades de esta clase son modificables.
type: docs
weight: 4811
url: /es/aspose.slides/portionformat/
---
## PortionFormat clase


Esta clase contiene las propiedades de formato de porción de texto. A diferencia de [IPortionFormatEffectiveData](../iportionformateffectivedata/), todas las propiedades de esta clase son modificables.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara con el objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aun cuando según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aun cuando según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Devuelve el Id de un idioma alternativo. Leer [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Devuelve el identificador del marcador. Leer [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Devuelve la información de fuente de script complejo. Null significa que la fuente no está definida y debe heredarse del Master. Leer [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Devuelve la información de fuente de Asia Oriental. Null significa que la fuente no está definida y debe heredarse del Master. Leer [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Devuelve las propiedades de texto [EffectFormat](../effectformat/). No se aplica herencia. Solo lectura [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Devuelve el texto de superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Leer **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Devuelve las propiedades de texto [FillFormat](../fillformat/). No se aplica herencia. Solo lectura [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Determina si la fuente está en negrita. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Devuelve la altura de fuente de una porción. **std::numeric_limits<float>::quiet_NaN()** significa que la altura no está definida y debe heredarse del Master. Leer **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Determina si la fuente está en cursiva. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Devuelve el tipo de subrayado de texto. No se aplica herencia. Leer [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Devuelve el color usado para resaltar un texto. No se aplica herencia. Solo lectura [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Devuelve el hipervínculo definido para el clic del ratón. Leer [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Gestor de hipervínculos. Solo lectura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Devuelve el hipervínculo definido para pasar el ratón por encima. Leer [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Determina si el estilo de subrayado tiene sus propias propiedades [FillFormat](../fillformat/) o las hereda de las propiedades [FillFormat](../fillformat/) del texto. Leer [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Determina si el estilo de subrayado tiene sus propias propiedades [LineFormat](../lineformat/) o las hereda de las propiedades [LineFormat](../lineformat/) del texto. Leer [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Devuelve el tamaño de fuente mínimo, para el cual se debe activar el kerning. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Leer **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Devuelve el Id de un idioma de corrección. Se usa para comprobar ortografía y gramática. Leer [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Devuelve la información de fuente latina. Null significa que la fuente no está definida y debe heredarse del Master. Leer [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Devuelve las propiedades [LineFormat](../lineformat/) para delineado de texto. No se aplica herencia. Solo lectura [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Determina si la altura de un texto debe normalizarse. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Devuelve el objeto Parent_Immediate. Solo lectura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Devuelve el padre [IPresentationComponent](../ipresentationcomponent/). Solo lectura [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Determina si el texto no debe ser corregido. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Determina si la etiqueta inteligente debe limpiarse. No se aplica herencia. Leer **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Devuelve el incremento del espaciado intercarácter. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Leer **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Obtiene un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, la corrección ortográfica está permitida. El valor predeterminado es **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Devuelve el tipo de tachado de un texto. No se aplica herencia. Leer [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Devuelve la información de fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Master. Leer [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Devuelve el tipo de capitalización del texto. No se aplica herencia. Leer [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Devuelve las propiedades de la línea de subrayado [FillFormat](../fillformat/). No se aplica herencia. Solo lectura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Devuelve las propiedades [LineFormat](../lineformat/) usadas para delinear la línea de subrayado. No se aplica herencia. Solo lectura [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtiene los datos de formato de porción efectivos con la herencia aplicada. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Devuelve el código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
|  [PortionFormat](./portionformat/)() | Inicializa una nueva instancia de la clase [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Establece el Id de un idioma alternativo. Escribir [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Establece el identificador del marcador. Escribir [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Establece la información de fuente de script complejo. Null significa que la fuente no está definida y debe heredarse del Master. Escribir [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Establece la información de fuente de Asia Oriental. Null significa que la fuente no está definida y debe heredarse del Master. Escribir [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Establece el texto de superíndice o subíndice. Valor de -100% (subíndice) a 100% (superíndice). **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Escribir **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Determina si la fuente está en negrita. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Establece la altura de fuente de una porción. **std::numeric_limits<float>::quiet_NaN()** significa que la altura no está definida y debe heredarse del Master. Escribir **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Determina si la fuente está en cursiva. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Establece el tipo de subrayado de texto. No se aplica herencia. Escribir [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Establece el hipervínculo definido para el clic del ratón. Escribir [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Establece el hipervínculo definido para pasar el ratón por encima. Escribir [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Determina si el estilo de subrayado tiene sus propias propiedades [FillFormat](../fillformat/) o las hereda de las propiedades [FillFormat](../fillformat/) del texto. Escribir [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Determina si el estilo de subrayado tiene sus propias propiedades [LineFormat](../lineformat/) o las hereda de las propiedades [LineFormat](../lineformat/) del texto. Escribir [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Establece el tamaño de fuente mínimo, para el cual se debe activar el kerning. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Escribir **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Establece el Id de un idioma de corrección. Se usa para comprobar ortografía y gramática. Escribir [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Establece la información de fuente latina. Null significa que la fuente no está definida y debe heredarse del Master. Escribir [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Determina si la altura de un texto debe normalizarse. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Determina si el texto no debe ser corregido. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Determina si la etiqueta inteligente debe limpiarse. No se aplica herencia. Escribir **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Establece el incremento del espaciado intercarácter. **std::numeric_limits<float>::quiet_NaN()** significa que el valor no está definido y debe heredarse del Master. Escribir **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto. Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto. Cuando se establece en true, la corrección ortográfica está permitida. El valor predeterminado es **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Establece el tipo de tachado de un texto. No se aplica herencia. Escribir [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Establece la información de fuente simbólica. Null significa que la fuente no está definida y debe heredarse del Master. Escribir [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Establece el tipo de capitalización del texto. No se aplica herencia. Escribir [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Observaciones


Esta clase se usa para devolver y manipular las propiedades de formato de porción de texto definidas para una porción específica. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores efectivos de los parámetros de formato, incluidos los heredados, debe usar el método [PortionFormat::GetEffective](./geteffective/) que devuelve una instancia [IPortionFormatEffectiveData](../iportionformateffectivedata/).

El siguiente ejemplo muestra cómo asignar la fuente latina a una porción de [Paragraph](../paragraph/) en PowerPoint [Presentation](../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides usa estos identificadores especiales (similares a los usados en PowerPoint):
// +mn-lt - Body Font Latin (Minor Latin Font) => +mn-lt - Fuente del cuerpo Latin (Fuente Latin Menor)
// +mj-lt -Heading Font Latin (Major Latin Font) => +mj-lt -Heading Fuente del encabezado Latin (Fuente Latin Mayor)
// +mn-ea - Body Font East Asian (Minor East Asian Font) => +mn-ea - Fuente del cuerpo East Asian (Fuente East Asian Menor)
// +mj-ea - Body Font East Asian (Minor East Asian Font) => +mj-ea - Fuente del cuerpo East Asian (Fuente East Asian Menor)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Ver también

* Clase [BasePortionFormat](../baseportionformat/)
* Clase [IPortionFormat](../iportionformat/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)