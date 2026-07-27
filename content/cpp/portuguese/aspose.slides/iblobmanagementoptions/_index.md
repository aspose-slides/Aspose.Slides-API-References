---
title: IBlobManagementOptions
second_title: Referência da API Aspose.Slides para C++
description: Um Binary Large Object (BLOB) é um dado binário armazenado como uma única entidade - ou seja, BLOB pode ser um áudio, vídeo ou a própria apresentação. Diversas técnicas são usadas para otimizar o consumo de memória ao trabalhar com BLOBs - que já estavam armazenados na apresentação ou podem ser adicionados posteriormente programaticamente. Usando IBlobManagementOptions você pode alterar diferentes aspectos de comportamento relacionados ao tratamento de BLOBs durante a vida útil da instância IPresentation.
type: docs
weight: 1535
url: /pt/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions classe


Um Objeto Binário Grande (BLOB) é um dado binário armazenado como uma única entidade - i.e. BLOB pode ser um áudio, vídeo ou a própria apresentação. Diversas técnicas são usadas para otimizar o consumo de memória ao trabalhar com BLOBs - que já estavam armazenados na apresentação ou podem ser adicionados posteriormente por programação. Usando [IBlobManagementOptions](./) você pode alterar diferentes aspectos de comportamento relacionados ao manuseio de BLOBs durante o tempo de vida da instância [IPresentation](../ipresentation/).

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para fins internos. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui drasticamente o consumo de memória, mas requer permissões para criar arquivos. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode gerar alto consumo de memória. Use esta propriedade para ajustar o comportamento ao seu ambiente ou requisitos. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | Esta propriedade define se uma instância da classe [Presentation](../presentation/) pode ser proprietária da origem - arquivo ou stream - durante a vida da instância. Se a instância for proprietária, ela bloqueia a origem. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a origem (stream ou arquivo) não pode ser alterada durante a vida da instância [Presentation](../presentation/). Este é um exemplo: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | O caminho raiz onde os arquivos temporários serão criados. O diretório temporário [System](../../system/) será usado por padrão. O processo de hospedagem deve ter permissões para criar arquivos e pastas lá. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analítico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência o objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui muito o consumo de memória, mas requer permissões para criar arquivos. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode levar a alto uso de memória. Use esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | Esta propriedade define se uma instância da classe [Presentation](../presentation/) pode ser proprietária da origem – arquivo ou fluxo – durante a vida da instância. Se a instância for proprietária, ela bloqueia a origem. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a origem (fluxo ou arquivo) não pode ser alterada durante a vida da instância de [Presentation](../presentation/). Este é um exemplo: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | O caminho raiz onde os arquivos temporários serão criados. O diretório temporário [System](../../system/) será usado por padrão. O processo hospedeiro deve ter permissões para criar arquivos e pastas lá. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)