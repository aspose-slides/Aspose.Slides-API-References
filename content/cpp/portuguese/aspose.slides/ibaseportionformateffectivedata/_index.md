---
title: IBasePortionFormatEffectiveData
second_title: Referência da API Aspose.Slides para C++
description: Interface base para objetos imutáveis que contêm propriedades efetivas de formatação de porções de texto.
type: docs
weight: 1470
url: /pt/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData classe


Base interface for immutable objects which contain effective text portion formatting properties.

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Retorna o Id de um idioma alternativo. Somente leitura [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Retorna as informações da fonte de script complexo. Somente leitura [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Retorna as informações da fonte Leste-Asiática. Somente leitura [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | Retorna as propriedades de texto [EffectFormat](../effectformat/). Somente leitura [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Retorna o texto sobrescrito ou subescrito. Valor de -100% (subescrito) a 100% (sobrescrito). Somente leitura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | Retorna as propriedades de texto [FillFormat](../fillformat/). Somente leitura [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](./get_fontbold/)() | Determina se a fonte está em negrito. Somente leitura **bool**. |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Retorna a altura da fonte da porção de texto, em pontos. Somente leitura **float**. |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | Determina se a fonte está em itálico. Somente leitura **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Retorna o tipo de sublinhado de texto. Somente leitura [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | Retorna a cor usada para destacar um texto. Somente leitura [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Determina se o estilo de sublinhado tem propriedades próprias [FillFormat](../fillformat/) ou herda das propriedades [FillFormat](../fillformat/) do texto. Somente leitura **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Determina se o estilo de sublinhado tem propriedades próprias [LineFormat](../lineformat/) ou herda das propriedades [LineFormat](../lineformat/) do texto. Somente leitura **bool**. |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Retorna o tamanho mínimo da fonte, para o qual o kerning deve ser ativado. Somente leitura **float**. |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | Determina se os números devem ignorar o layout vertical de texto específico de idioma oriental. Somente leitura **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Retorna o Id de um idioma. Somente leitura [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Retorna as informações da fonte Latina. Somente leitura [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | Retorna as propriedades [LineFormat](../lineformat/) para contorno de texto. Somente leitura [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | Determina se a altura de um texto deve ser normalizada. Somente leitura **bool**. |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | Determina se o texto não deve ser revisado. Somente leitura **bool**. |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Determina se a tag inteligente deve ser limpa. Somente leitura **bool**. |
| virtual **float** [get_Spacing](./get_spacing/)() | Retorna o incremento de espaçamento intercaractere, em pontos. Somente leitura **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Retorna o tipo de tachado de um texto. Somente leitura [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Retorna as informações da fonte simbólica. Somente leitura [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Retorna o tipo de capitalização de texto. Somente leitura [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Retorna as propriedades da linha de sublinhado [FillFormat](../fillformat/). Somente leitura [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Retorna as propriedades [LineFormat](../lineformat/) usadas para contornar a linha de sublinhado. Somente leitura [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)