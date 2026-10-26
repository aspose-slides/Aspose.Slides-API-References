---
title: BasePortionFormat
second_title: Referência da API Aspose.Slides para C++
description: Propriedades de formatação de porção de texto comuns.
type: docs
weight: 144
url: /pt/aspose.slides/baseportionformat/
---
## BasePortionFormat classe

Propriedades de formatação de porção de texto comuns.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara com o objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Retorna o Id de um idioma alternativo. Leia [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Retorna as informações da fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leia [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Retorna as informações da fonte do Leste Asiático. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leia [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Retorna as propriedades de texto [EffectFormat](../effectformat/). Nenhuma herança aplicada. Somente leitura [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Retorna o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **std::numeric_limits<float>::quiet_NaN()** indica que o valor está indefinido e deve ser herdado do Mestre. Leia **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Retorna as propriedades de texto [FillFormat](../fillformat/). Nenhuma herança aplicada. Somente leitura [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Determina se a fonte está em negrito. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Retorna a altura da fonte de uma porção. **std::numeric_limits<float>::quiet_NaN()** indica que a altura está indefinida e deve ser herdada do Mestre. Leia **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Determina se a fonte está itálica. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Retorna o tipo de sublinhado do texto. Nenhuma herança aplicada. Leia [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Retorna a cor usada para realçar um texto. Nenhuma herança aplicada. Somente leitura [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Determina se o estilo de sublinhado tem propriedades próprias [FillFormat](../fillformat/) ou se as herda das propriedades [FillFormat](../fillformat/) do texto. Leia [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Determina se o estilo de sublinhado tem propriedades próprias [LineFormat](../lineformat/) ou se as herda das propriedades [LineFormat](../lineformat/) do texto. Leia [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Retorna o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **std::numeric_limits<float>::quiet_NaN()** indica que o valor está indefinido e deve ser herdado do Mestre. Leia **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Determina se os números devem ignorar o layout vertical de texto específico de idiomas do leste. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Retorna o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical. Leia [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Retorna as informações da fonte latina. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leia [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Retorna as propriedades [LineFormat](../lineformat/) para contorno de texto. Nenhuma herança aplicada. Somente leitura [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retorna o objeto Parent_Immediate. Somente leitura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retorna o [IPresentationComponent](../ipresentationcomponent/) pai. Somente leitura [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Determina se o texto não deve ser revisado. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Retorna o incremento de espaçamento entre caracteres. **std::numeric_limits<float>::quiet_NaN()** indica que o valor está indefinido e deve ser herdado do Mestre. Leia **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Obtém um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Retorna o tipo de tachado de um texto. Nenhuma herança aplicada. Leia [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Retorna as informações da fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leia [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Retorna o tipo de capitalização de texto. Nenhuma herança aplicada. Leia [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Retorna as propriedades da linha de sublinhado [FillFormat](../fillformat/). Nenhuma herança aplicada. Somente leitura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Retorna as propriedades [LineFormat](../lineformat/) usadas para contornar a linha de sublinhado. Nenhuma herança aplicada. Somente leitura [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retorna o código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Define o Id de um idioma alternativo. Grave [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Define as informações da fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Grave [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Define as informações da fonte do Leste Asiático. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Grave [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **std::numeric_limits<float>::quiet_NaN()** indica que o valor está indefinido e deve ser herdado do Mestre. Grave **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Determina se a fonte está em negrito. Nenhuma herança aplicada. Grave [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Define a altura da fonte de uma porção. **std::numeric_limits<float>::quiet_NaN()** indica que a altura está indefinida e deve ser herdada do Mestre. Grave **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Determina se a fonte está itálica. Nenhuma herança aplicada. Grave [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Define o tipo de sublinhado do texto. Nenhuma herança aplicada. Grave [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Determina se o estilo de sublinhado tem propriedades próprias [FillFormat](../fillformat/) ou se as herda das propriedades [FillFormat](../fillformat/) do texto. Grave [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Determina se o estilo de sublinhado tem propriedades próprias [LineFormat](../lineformat/) ou se as herda das propriedades [LineFormat](../lineformat/) do texto. Grave [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **std::numeric_limits<float>::quiet_NaN()** indica que o valor está indefinido e deve ser herdado do Mestre. Grave **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Determina se os números devem ignorar o layout vertical de texto específico de idiomas do leste. Nenhuma herança aplicada. Grave [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Define o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical. Grave [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Define as informações da fonte latina. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Grave [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada. Grave [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Determina se o texto não deve ser revisado. Nenhuma herança aplicada. Grave [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Define o incremento de espaçamento entre caracteres. **std::numeric_limits<float>::quiet_NaN()** indica que o valor está indefinido e deve ser herdado do Mestre. Grave **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Define o tipo de tachado de um texto. Nenhuma herança aplicada. Grave [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Define as informações da fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Grave [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Define o tipo de capitalização de texto. Nenhuma herança aplicada. Grave [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (ao invés de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [PVIObject](../pviobject/)
* Classe [IBasePortionFormat](../ibaseportionformat/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)