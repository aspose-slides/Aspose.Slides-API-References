---
title: LayoutSlideHeaderFooterManager
second_title: Referência de API Aspose.Slides para C++
description: Representa o gerenciador que mantém o comportamento do rodapé do slide de layout, placeholders de data e hora, números de página e todos os placeholders filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.
type: docs
weight: 4317
url: /pt/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager classe


Representa o gerenciador que mantém o comportamento do rodapé do slide de layout, placeholders de data e hora, número de página e todos os placeholders filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo de referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Obtém valor indicando que um placeholder de data e hora está presente. Read**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Obtém valor indicando que um placeholder de rodapé está presente. Read **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Obtém valor indicando que um placeholder de número de página está presente. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade, não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade, não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Define o texto no placeholder de data e hora do slide de layout e em todos os placeholders de data e hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Altera a visibilidade do placeholder de data e hora do slide de layout e de todos os placeholders de data e hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Define o texto no placeholder de data e hora do slide. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Altera a visibilidade do placeholder de data e hora do slide. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Define o texto no placeholder de rodapé do slide de layout e em todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Altera a visibilidade do placeholder de rodapé do slide de layout e de todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide mestre. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Define o texto no placeholder de rodapé do slide. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Altera a visibilidade do placeholder de rodapé do slide. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Altera a visibilidade do placeholder de número de página do slide de layout e de todos os placeholders de número de página filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Altera a visibilidade do placeholder de número de página do slide. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* Classe [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)