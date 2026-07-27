---
title: BulletFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa as propriedades de formatação de marcadores de parágrafo.
type: docs
weight: 248
url: /pt/aspose.slides/bulletformat/
---
## BulletFormat classe

Representa as propriedades de formatação de marcadores de parágrafo.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Define deslocamentos padrão diferentes de zero para o Indent e MarginLeft efetivos do parágrafo quando os marcadores estão habilitados (como o PowerPoint faz ao habilitar marcadores/numerção de parágrafos). Se os marcadores estiverem desabilitados, apenas redefine o Indent e MarginLeft do parágrafo (como o PowerPoint faz ao desabilitar marcadores/numerção de parágrafos). Os deslocamentos de recuo são aplicados em relação ao contexto atual do marcador – IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos diferentes de zero são aplicados ao Indent e MarginLeft efetivos do parágrafo atual (fazendo com que os valores resultantes sejam valores locais). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara com o objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| char16_t [get_Char](./get_char/)() override | Retorna o caractere do marcador de um parágrafo sem herança. Somente leitura **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Retorna o formato de cor de um marcador de um parágrafo sem herança. Somente leitura [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Retorna a fonte do marcador de um parágrafo sem herança. Somente leitura [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Retorna a altura do marcador de um parágrafo sem herança. O valor std::numeric_limits<float>::quiet_NaN() indica que o marcador herda a altura da primeira porção no parágrafo. Somente leitura **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Determina se o marcador tem cor própria ou a herda da primeira porção no parágrafo. **[NullableBool::True](../nullablebool/)** se o marcador tem cor própria e **[NullableBool::False](../nullablebool/)** se o marcador herda a cor da primeira porção no parágrafo. Somente leitura [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Determina se o marcador tem fonte própria ou a herda da primeira porção no parágrafo. **[NullableBool::True](../nullablebool/)** se o marcador tem fonte própria e **[NullableBool::False](../nullablebool/)** se o marcador herda a fonte da primeira porção no parágrafo. Somente leitura [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Retorna o primeiro número usado para o grupo de marcadores numerados sem herança. Somente leitura **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Retorna o estilo de um marcador numerado sem herança. Somente leitura [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retorna o objeto Parent_Immediate. Somente leitura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retorna o [IPresentationComponent](../ipresentationcomponent/) pai. Somente leitura [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Retorna a imagem usada como marcador em um parágrafo sem herança. Somente leitura [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Retorna o tipo de marcador de um parágrafo sem herança. Somente leitura [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtém os dados de formatação de marcador efetivos com a herança aplicada. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retorna o código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Char](./set_char/)(char16_t) override | Define o caractere do marcador de um parágrafo sem herança. Escrita **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Define a fonte do marcador de um parágrafo sem herança. Escrita [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Define a altura do marcador de um parágrafo sem herança. O valor std::numeric_limits<float>::quiet_NaN() indica que o marcador herda a altura da primeira porção no parágrafo. Escrita **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Determina se o marcador tem cor própria ou a herda da primeira porção no parágrafo. **[NullableBool::True](../nullablebool/)** se o marcador tem cor própria e **[NullableBool::False](../nullablebool/)** se o marcador herda a cor da primeira porção no parágrafo. Escrita [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Determina se o marcador tem fonte própria ou a herda da primeira porção no parágrafo. **[NullableBool::True](../nullablebool/)** se o marcador tem fonte própria e **[NullableBool::False](../nullablebool/)** se o marcador herda a fonte da primeira porção no parágrafo. Escrita [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Define o primeiro número usado para o grupo de marcadores numerados sem herança. Escrita **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Define o estilo de um marcador numerado sem herança. Escrita [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Define o tipo de marcador de um parágrafo sem herança. Escrita [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas de dados. |

## Ver também

* Classe [PVIObject](../pviobject/)
* Classe [IBulletFormat](../ibulletformat/)
* Espaço de nomes [Aspose::Slides](../)
* Library [Aspose.Slides](../../)