---
title: IBasePortionFormat
second_title: Referência da API Aspose.Slides para C++
description: Esta classe contém as propriedades de formatação de porções de texto. Ao contrário de IPortionFormatEffectiveData, todas as propriedades desta classe são graváveis.
type: docs
weight: 1457
url: /pt/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat classe


Esta classe contém as propriedades de formatação de porções de texto. Ao contrário de [IPortionFormatEffectiveData](../iportionformateffectivedata/), todas as propriedades desta classe são graváveis.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Retorna o Id de um idioma alternativo. Leia [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Retorna as informações da fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leia [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Retorna as informações da fonte East Asian. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leia [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Retorna as propriedades de texto [EffectFormat](../effectformat/). Nenhuma herança aplicada. Somente leitura [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Retorna o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **std::numeric_limits<float>::quiet_NaN()** significa que o valor está indefinido e deve ser herdado do Mestre. Leia **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Retorna as propriedades de texto [FillFormat](../fillformat/). Nenhuma herança aplicada. Somente leitura [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Determina se a fonte está em negrito. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Retorna a altura da fonte de uma porção. **std::numeric_limits<float>::quiet_NaN()** significa que a altura está indefinida e deve ser herdada do Mestre. Leia **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Determina se a fonte está itálica. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Retorna o tipo de sublinhado do texto. Nenhuma herança aplicada. Leia [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Retorna a cor usada para destacar um texto. Nenhuma herança aplicada. Somente leitura [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Determina se o estilo de sublinhado tem propriedades próprias [FillFormat](../fillformat/) ou as herda das propriedades [FillFormat](../fillformat/) do texto. Leia [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Determina se o estilo de sublinhado tem propriedades próprias [LineFormat](../lineformat/) ou as herda das propriedades [LineFormat](../lineformat/) do texto. Leia [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Retorna o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **std::numeric_limits<float>::quiet_NaN()** significa que o valor está indefinido e deve ser herdado do Mestre. Leia **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Determina se os números devem ignorar o layout vertical específico de texto de idioma oriental. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Retorna o Id de um idioma de correção. Usado para verificação ortográfica e gramatical. Leia [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Retorna as informações da fonte Latin. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leia [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Retorna as propriedades [LineFormat](../lineformat/) para contorno de texto. Nenhuma herança aplicada. Somente leitura [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Determina se o texto não deve ser corrigido. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Retorna o incremento de espaçamento entre caracteres. **std::numeric_limits<float>::quiet_NaN()** significa que o valor está indefinido e deve ser herdado do Mestre. Leia **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Obtém um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Retorna o tipo de tachado de um texto. Nenhuma herança aplicada. Leia [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Retorna as informações da fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Leia [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Retorna o tipo de capitalização de texto. Nenhuma herança aplicada. Leia [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Retorna as propriedades da linha de sublinhado [FillFormat](../fillformat/). Nenhuma herança aplicada. Somente leitura [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Retorna as propriedades [LineFormat](../lineformat/) usadas para contornar a linha de sublinhado. Nenhuma herança aplicada. Somente leitura [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Define o Id de um idioma alternativo. Escreva [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Define as informações da fonte de script complexo. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Escreva [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Define as informações da fonte East Asian. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Escreva [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Define o texto sobrescrito ou subscrito. Valor de -100% (subscrito) a 100% (sobrescrito). **std::numeric_limits<float>::quiet_NaN()** significa que o valor está indefinido e deve ser herdado do Mestre. Escreva **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Determina se a fonte está em negrito. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Define a altura da fonte de uma porção. **std::numeric_limits<float>::quiet_NaN()** significa que a altura está indefinida e deve ser herdada do Mestre. Escreva **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Determina se a fonte está itálica. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Define o tipo de sublinhado do texto. Nenhuma herança aplicada. Escreva [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Determina se o estilo de sublinhado tem propriedades próprias [FillFormat](../fillformat/) ou as herda das propriedades [FillFormat](../fillformat/) do texto. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Determina se o estilo de sublinhado tem propriedades próprias [LineFormat](../lineformat/) ou as herda das propriedades [LineFormat](../lineformat/) do texto. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. **std::numeric_limits<float>::quiet_NaN()** significa que o valor está indefinido e deve ser herdado do Mestre. Escreva **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Determina se os números devem ignorar o layout vertical específico de idioma oriental. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Define o Id de um idioma de correção. Usado para verificação ortográfica e gramatical. Escreva [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Define as informações da fonte Latin. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Escreva [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Determina se o texto não deve ser corrigido. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Define o incremento de espaçamento entre caracteres. **std::numeric_limits<float>::quiet_NaN()** significa que o valor está indefinido e deve ser herdado do Mestre. Escreva **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Define um valor que indica se a verificação ortográfica está habilitada para a porção de texto. Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas. Quando definida como true, a verificação ortográfica é permitida. O valor padrão é **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Define o tipo de tachado de um texto. Nenhuma herança aplicada. Escreva [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Define as informações da fonte simbólica. Null significa que a fonte está indefinida e deve ser herdada do Mestre. Escreva [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Define o tipo de capitalização de texto. Nenhuma herança aplicada. Escreva [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações


Esta classe é usada para retornar e manipular as propriedades de formatação de porções de texto definidas para a porção específica. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam "indefinido".

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [IPortionFormat::GetEffective](../iportionformat/geteffective/) que retorna uma instância [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)