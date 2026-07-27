---
title: IMasterSlideHeaderFooterManager
second_title: Referência da API Aspose.Slides para C++
description: Representa o gerenciador que contém o comportamento do rodapé do slide mestre, dos marcadores de data/hora, número de página e de todos os marcadores filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.
type: docs
weight: 2952
url: /pt/aspose.slides/imasterslideheaderfootermanager/
---
## IMasterSlideHeaderFooterManager classe


Representa o gerenciador que contém o comportamento do rodapé do slide mestre, dos marcadores de data/hora, número de página e todos os marcadores filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre.

```cpp
class IMasterSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Obtém o valor que indica que um marcador de data/hora está presente. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Obtém o valor que indica que um marcador de rodapé está presente. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Obtém o valor que indica que um marcador de número de página está presente. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Define o texto no marcador de data/hora do slide mestre e em todos os marcadores de data/hora filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Altera a visibilidade do marcador de data/hora do slide mestre e de todos os marcadores de data/hora filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Define o texto no marcador de data/hora do slide. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Altera a visibilidade do marcador de data/hora do slide. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Define o texto no marcador de rodapé do slide mestre e em todos os marcadores de rodapé filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Altera a visibilidade do marcador de rodapé do slide mestre e de todos os marcadores de rodapé filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Define o texto no marcador de rodapé do slide. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Altera a visibilidade do marcador de rodapé do slide. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Altera a visibilidade do marcador de número de página do slide mestre e de todos os marcadores de número de página filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Altera a visibilidade do marcador de número de página do slide. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como weak pointer (em vez de shared). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)