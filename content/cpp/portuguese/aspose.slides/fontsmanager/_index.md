---
title: FontsManager
second_title: Referência da API Aspose.Slides para C++
description: Gerencia fontes em toda a apresentação.
type: docs
weight: 989
url: /pt/aspose.slides/fontsmanager/
---
## FontsManager classe

Gerencia fontes em toda a apresentação.

```cpp
class FontsManager : public Aspose::Slides::IFontsManager
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [AddEmbeddedFont](./addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Adiciona a fonte incorporada |
| void [AddEmbeddedFont](./addembeddedfont/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Adiciona a fonte incorporada |
| virtual void [AddEmbeddedFont](../ifontsmanager/addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) | Adiciona a fonte incorporada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo de referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo de valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/)\> [get_FontFallBackRule](./get_fontfallbackrule/)(**int32_t**) override | Retorna a regra no índice especificado para substituições corretas pela funcionalidade de fallback. Somente leitura [Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\> [get_FontFallBackRulesCollection](./get_fontfallbackrulescollection/)() override | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições corretas pela funcionalidade de fallback. Leia [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\> [get_FontSubstRule](./get_fontsubstrule/)(**int32_t**) override | Retorna a regra de substituição de fonte no índice especificado para uso ao renderizar. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\> [get_FontSubstRuleList](./get_fontsubstrulelist/)() override | Substituições de fonte para usar ao renderizar. Somente leitura [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados de contador de referência associada ao objeto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetEmbeddedFonts](./getembeddedfonts/)() override | Retorna as fontes incorporadas na apresentação |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](./getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::FontStyleType](../fontstyletype/)) override | Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](../ifontsmanager/getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [FontStyleType](../fontstyletype/)) | Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados. |
| [Aspose::Slides::EmbeddingLevel](../embeddinglevel/) [GetFontEmbeddingLevel](./getfontembeddinglevel/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/)) override | Determina o nível de incorporação de uma fonte a partir do array de bytes fornecido e do nome da fonte. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetFonts](./getfonts/)() override | Retorna as fontes usadas na apresentação |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)() override | Obtém as informações sobre fontes que serão substituídas na renderização da apresentação. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)([System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Obtém as informações sobre fontes que serão substituídas durante a renderização dos slides especificados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui a contagem de referência compartilhada pelo valor especificado. |
| void [RemoveEmbeddedFont](./removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Remove a fonte incorporada |
| virtual void [RemoveEmbeddedFont](../ifontsmanager/removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Remove a fonte incorporada |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Substitui a fonte na apresentação |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\>) override | Substitui a fonte na apresentação usando as informações fornecidas em [FontSubstRule](../fontsubstrule/) |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Substitui a fonte na apresentação usando as informações fornecidas na coleção de [FontSubstRule](../fontsubstrule/) |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Substitui a fonte na apresentação |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRule](../ifontsubstrule/)\>) | Substitui a fonte na apresentação usando as informações fornecidas em [IFontSubstRule](../ifontsubstrule/) |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Substitui a fonte na apresentação usando as informações fornecidas na coleção de [IFontSubstRule](../ifontsubstrule/) |
| void [set_FontFallBackRulesCollection](./set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) override | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas por funcionalidade de fallback. Escreva [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| virtual void [set_FontFallBackRulesCollection](../ifontsmanager/set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas por funcionalidade de fallback. Escreva [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| void [set_FontSubstRuleList](./set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Substituições de fonte a usar ao renderizar. Escreva [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [set_FontSubstRuleList](../ifontsmanager/set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Substituições de fonte a usar ao renderizar. Escreva [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa a contagem de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna a contagem de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa a contagem de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa a contagem de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Observações

O exemplo a seguir mostra como adicionar fontes incorporadas ao PowerPoint [Presentation](../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Salvar a apresentação
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [IFontsManager](../ifontsmanager/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)