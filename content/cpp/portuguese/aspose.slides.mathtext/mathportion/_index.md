---
title: MathPortion
second_title: Referência da API Aspose.Slides para C++
description: Representa uma porção com contexto matemático interno.
type: docs
weight: 1041
url: /pt/aspose.slides.mathtext/mathportion/
---
## MathPortion classe

Represents a portion with mathematical context inside.

```cpp
class MathPortion : public Aspose::Slides::Portion,
                    public Aspose::Slides::MathText::IMathPortion
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [AddField](../../aspose.slides/portion/addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../../aspose.slides/ifieldtype/)\>) override | Converte esta porção para o campo atualizado automaticamente. |
| void [AddField](../../aspose.slides/portion/addfield/)([System::String](../../system/string/)) override | Converte esta porção para o campo atualizado automaticamente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../../aspose.slides/ifield/)\> [get_Field](../../aspose.slides/portion/get_field/)() override | Retorna um campo desta porção. [IField](../../aspose.slides/ifield/) somente leitura. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathParagraph](../imathparagraph/)\> [get_MathParagraph](./get_mathparagraph/)() override | Parágrafo matemático |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../../aspose.slides/iportionformat/)\> [get_PortionFormat](../../aspose.slides/portion/get_portionformat/)() override | Retorna objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada. [IPortionFormat](../../aspose.slides/iportionformat/) somente leitura. |
| [System::String](../../system/string/) [get_Text](../../aspose.slides/portion/get_text/)() override | Obtém o texto simples de uma porção. [System::String](../../system/string/) leitura. |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](../../aspose.slides/portion/getcoordinates/)() override | Obtém as coordenadas do início da porção. A coordenada X do ponto representa o início da porção a partir do primeiro caractere, incluindo o espaçamento lateral esquerdo. A coordenada Y inclui o espaçamento superior. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógua do método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](../../aspose.slides/portion/getrect/)() override | Obtém as coordenadas do retângulo que delimita a porção. O retângulo inclui todas as linhas de texto na porção, incluindo as vazias. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógua da chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógua do operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
|  [MathPortion](./mathportion/)() | Inicializa uma nova instância da classe [MathPortion](./). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógua do método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
|  [Portion](../../aspose.slides/portion/portion/)() | Inicializa uma nova instância da classe [Portion](../../aspose.slides/portion/). |
|  [Portion](../../aspose.slides/portion/portion/)([System::String](../../system/string/)) | Inicializa uma nova instância da classe [Portion](../../aspose.slides/portion/). |
|  [Portion](../../aspose.slides/portion/portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](../../aspose.slides/portion/)\>) | Inicializa uma nova instância da classe [Portion](../../aspose.slides/portion/). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [RemoveField](../../aspose.slides/portion/removefield/)() override | Converte esta porção de campo para a porção simples. |
| void [set_Text](../../aspose.slides/portion/set_text/)([System::String](../../system/string/)) override | Define o texto simples de uma porção. [System::String](../../system/string/) escrita. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógua do método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Veja também

* Classe [Portion](../../aspose.slides/portion/)
* Classe [IMathPortion](../imathportion/)
* Namespace [Aspose::Slides::MathText](../)
* Biblioteca [Aspose.Slides](../../)