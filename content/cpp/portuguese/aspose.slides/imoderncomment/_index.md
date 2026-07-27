---
title: IModernComment
second_title: Aspose.Slides para Referência da API C++
description: Representa um comentário em um slide.
type: docs
weight: 2965
url: /pt/aspose.slides/imoderncomment/
---
## IModernComment classe

Representa um comentário em um slide.

```cpp
class IModernComment : public virtual Aspose::Slides::IComment
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../icomment/get_author/)() | Retorna o autor de um comentário. Somente leitura [ICommentAuthor](../icommentauthor/). |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](../icomment/get_createdtime/)() | Retorna o horário de criação de um comentário. Definir esta propriedade como [DateTime::MinValue](../../system/datetime/minvalue/) significa que nenhum horário de comentário está definido. Leitura [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../icomment/get_parentcomment/)() | Obtém o comentário pai. Leitura [IComment](../icomment/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../icomment/get_position/)() | Retorna a posição de um comentário em um slide. Leitura [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() | Retorna uma forma associada ao comentário. Somente leitura [IShape](../ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../icomment/get_slide/)() | Retorna o slide pai de um comentário. Somente leitura [ISlide](../islide/). |
| virtual [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() | Retorna o status do comentário. Leitura [ModernCommentStatus](../moderncommentstatus/). |
| virtual [System::String](../../system/string/) [get_Text](../icomment/get_text/)() | Retorna o texto simples de um comentário de slide. Leitura [System::String](../../system/string/). |
| virtual **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() | Retorna o comprimento da seleção de texto no quadro de texto se o comentário estiver associado a [AutoShape](../autoshape/). Leitura **int32_t**. |
| virtual **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() | Retorna a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado a [AutoShape](../autoshape/). Leitura **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| virtual void [Remove](../icomment/remove/)() | Remove o comentário e todas as suas respostas da coleção pai. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_CreatedTime](../icomment/set_createdtime/)([System::DateTime](../../system/datetime/)) | Define o horário de criação de um comentário. Definir esta propriedade como [DateTime::MinValue](../../system/datetime/minvalue/) significa que nenhum horário de comentário está definido. Gravação [System::DateTime](../../system/datetime/). |
| virtual void [set_ParentComment](../icomment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) | Define o comentário pai. Gravação [IComment](../icomment/). |
| virtual void [set_Position](../icomment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Define a posição de um comentário em um slide. Gravação [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) | Define o status do comentário. Gravação [ModernCommentStatus](../moderncommentstatus/). |
| virtual void [set_Text](../icomment/set_text/)([System::String](../../system/string/)) | Define o texto simples de um comentário de slide. Gravação [System::String](../../system/string/). |
| virtual void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) | Define o comprimento da seleção de texto no quadro de texto se o comentário estiver associado a [AutoShape](../autoshape/). Gravação **int32_t**. |
| virtual void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) | Define a posição inicial da seleção de texto no quadro de texto se o comentário estiver associado a [AutoShape](../autoshape/). Gravação **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o enésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Ver também

* Classe [IComment](../icomment/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)