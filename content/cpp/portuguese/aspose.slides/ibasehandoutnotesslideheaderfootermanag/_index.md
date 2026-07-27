---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Referência da API Aspose.Slides para C++
description: Representa o gerenciador que contém o comportamento dos placeholders, incluindo o placeholder de cabeçalho para todos os tipos de slides de folhetos e notas.
type: docs
weight: 1431
url: /pt/aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
## IBaseHandoutNotesSlideHeaderFooterManag classe


Representa o gerenciador que contém o comportamento dos placeholders, incluindo o placeholder de cabeçalho para todos os tipos de slides de folhetos e notas.

```cpp
class IBaseHandoutNotesSlideHeaderFooterManag : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Obtém o valor que indica que um placeholder de data e hora está presente. Leitura**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Obtém o valor que indica que um placeholder de rodapé está presente. Leitura **bool**. |
| virtual **bool** [get_IsHeaderVisible](./get_isheadervisible/)() | Obtém o valor que indica que um placeholder de cabeçalho está presente. Leitura **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Obtém o valor que indica que um placeholder de número de página está presente. Leitura**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Define o texto no placeholder de data e hora do slide. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Altera a visibilidade do placeholder de data e hora do slide. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Define o texto no placeholder de rodapé do slide. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Altera a visibilidade do placeholder de rodapé do slide. |
| virtual void [SetHeaderText](./setheadertext/)([System::String](../../system/string/)) | Define o texto no placeholder de cabeçalho do slide. |
| virtual void [SetHeaderVisibility](./setheadervisibility/)(**bool**) | Altera a visibilidade do placeholder de cabeçalho do slide. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Altera a visibilidade do placeholder de número de página do slide. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Observações


O nome original da interface "IBaseHandoutNotesSlideHeaderFooterManager" foi truncado para "IBaseHandoutNotesSlideHeaderFooterManag" por compatibilidade COM (o comprimento do nome do tipo não deve exceder 39).
## Veja Também

* Classe [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)