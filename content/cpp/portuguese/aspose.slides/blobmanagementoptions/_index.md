---
title: BlobManagementOptions
second_title: Referência da API Aspose.Slides para C++
description: Representa opções que podem ser usadas para gerir regras de manipulação de BLOBs e outras configurações de BLOB.
type: docs
weight: 196
url: /pt/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions classe


Representa opções que podem ser usadas para gerenciar regras de manipulação de BLOBs e outras configurações de BLOB.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Cria novas opções padrão de gerenciamento de blob. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui consideravelmente o consumo de memória, mas requer permissões para criar arquivos. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é alcançado são empregados mecanismos alternativos (como arquivos temporários). Manter BLOBs na memória maximiza o desempenho, mas pode levar a alto uso de memória. Use esta propriedade para ajustar o comportamento ao seu ambiente ou requisitos. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Esta propriedade define se uma instância da classe [Presentation](../presentation/) pode ser proprietária da fonte – arquivo ou fluxo – durante a vida da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) não pode ser alterada durante a vida da instância de [Presentation](../presentation/). |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | O caminho raiz onde os arquivos temporários serão criados. O diretório temporário [System](../../system/) será usado por padrão. O processo de hospedagem deve ter permissões para criar arquivos e pastas lá. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Esta propriedade define se arquivos temporários podem ser criados ao trabalhar com BLOBs, o que diminui consideravelmente o consumo de memória, mas requer permissões para criar arquivos. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é alcançado são empregados mecanismos alternativos (como arquivos temporários). Manter BLOBs na memória maximiza o desempenho, mas pode levar a alto uso de memória. Use esta propriedade para ajustar o comportamento ao seu ambiente ou requisitos. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Esta propriedade define se uma instância da classe [Presentation](../presentation/) pode ser proprietária da fonte – arquivo ou fluxo – durante a vida da instância. Se a instância for proprietária, ela bloqueia a fonte. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a fonte (fluxo ou arquivo) não pode ser alterada durante a vida da instância de [Presentation](../presentation/). |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | O caminho raiz onde os arquivos temporários serão criados. O diretório temporário [System](../../system/) será usado por padrão. O processo de hospedagem deve ter permissões para criar arquivos e pastas lá. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IBlobManagementOptions](../iblobmanagementoptions/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)