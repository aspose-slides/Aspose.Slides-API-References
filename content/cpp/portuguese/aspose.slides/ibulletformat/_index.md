---
title: IBulletFormat
second_title: Aspose.Slides para C++ Referência da API
description: Representa as propriedades de formatação de marcadores de parágrafo.
type: docs
weight: 1561
url: /pt/aspose.slides/ibulletformat/
---
## IBulletFormat classe

Representa as propriedades de formatação de marcadores de parágrafo.

```cpp
class IBulletFormat : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | Define os deslocamentos padrão não-zero para o Indent e MarginLeft efetivos do parágrafo quando os marcadores estão habilitados (como o PowerPoint faz ao habilitar marcadores/numerção de parágrafo). Se os marcadores estiverem desabilitados, apenas redefine o Indent e MarginLeft do parágrafo (como o PowerPoint faz ao desabilitar marcadores/numerção de parágrafo). Os deslocamentos de recuo são aplicados em relação ao contexto atual do marcador – IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos de recuo não-zero são aplicados ao Indent e MarginLeft efetivos do parágrafo atual (fazendo com que os valores resultantes sejam valores locais). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual char16_t [get_Char](./get_char/)() | Retorna o caractere de marcador de um parágrafo sem herança. Leitura **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | Retorna o formato de cor de um marcador de um parágrafo sem herança. Somente leitura [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | Retorna a fonte do marcador de um parágrafo sem herança. Leitura [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | Retorna a altura do marcador de um parágrafo sem herança. O valor std::numeric_limits<float>::quiet_NaN() determina que o marcador herda a altura da primeira porção no parágrafo. Leitura **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | Determina se o marcador tem cor própria ou a herda da primeira porção no parágrafo. **[NullableBool::True](../nullablebool/)** se o marcador tem cor própria e **[NullableBool::False](../nullablebool/)** se o marcador herda a cor da primeira porção no parágrafo. Leitura [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | Determina se o marcador tem fonte própria ou a herda da primeira porção no parágrafo. **[NullableBool::True](../nullablebool/)** se o marcador tem fonte própria e **[NullableBool::False](../nullablebool/)** se o marcador herda a fonte da primeira porção no parágrafo. Leitura [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | Retorna o primeiro número usado para o grupo de marcadores numerados sem herança. Leitura **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | Retorna o estilo de um marcador numerado sem herança. Leitura [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Retorna a imagem usada como marcador em um parágrafo sem herança. Somente leitura [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | Retorna o tipo de marcador de um parágrafo sem herança. Leitura [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtém os dados de formatação efetiva do marcador com a herança aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_Char](./set_char/)(char16_t) | Define o caractere de marcador de um parágrafo sem herança. Escrita **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Define a fonte do marcador de um parágrafo sem herança. Escrita [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | Define a altura do marcador de um parágrafo sem herança. O valor std::numeric_limits<float>::quiet_NaN() determina que o marcador herda a altura da primeira porção no parágrafo. Escrita **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | Determina se o marcador tem cor própria ou a herda da primeira porção no parágrafo. **[NullableBool::True](../nullablebool/)** se o marcador tem cor própria e **[NullableBool::False](../nullablebool/)** se o marcador herda a cor da primeira porção no parágrafo. Escrita [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | Determina se o marcador tem fonte própria ou a herda da primeira porção no parágrafo. **[NullableBool::True](../nullablebool/)** se o marcador tem fonte própria e **[NullableBool::False](../nullablebool/)** se o marcador herda a fonte da primeira porção no parágrafo. Escrita [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | Define o primeiro número usado para o grupo de marcadores numerados sem herança. Escrita **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | Define o estilo de um marcador numerado sem herança. Escrita [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | Define o tipo de marcador de um parágrafo sem herança. Escrita [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamada diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamada diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamada diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamada diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver Também

* Classe [Object](../../system/object/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)