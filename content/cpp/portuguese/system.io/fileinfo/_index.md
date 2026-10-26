---
title: FileInfo
second_title: Referência da API Aspose.Slides para C++
description: "Representa um caminho para um arquivo e um arquivo referenciado por esse caminho, fornecendo métodos para manipulá-lo. Objetos desta classe devem ser alocados somente usando a função System::MakeObject(). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 274
url: /pt/system.io/fileinfo/
---
## FileInfo classe


Representa um caminho para um arquivo e um arquivo referenciado por esse caminho e fornece métodos para manipulá-lo. Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias desse tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Métodos

| Method | Description |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Abre um arquivo representado pelo objeto atual para escrita de texto usando codificação UTF-8, no modo 'Append' sem compartilhamento. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Copia o arquivo representado pelo objeto atual para o local especificado. Se o arquivo de destino já existir, a cópia falha. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Copia o arquivo representado pelo objeto atual para o local especificado. Um parâmetro indica se o arquivo de destino existente deve ser sobrescrito. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Cria um arquivo no local especificado pelo caminho representado pelo objeto atual e o abre para leitura e escrita, no modo truncar e sem compartilhamento. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Cria um arquivo no local especificado pelo caminho representado pelo objeto atual e o abre para escrita de texto usando codificação UTF-8 sem compartilhamento. |
| void [Decrypt](./decrypt/)() | NOT IMPLEMENTED. |
| void [Delete](./delete/)() override | Remove o arquivo representado pelo objeto atual. |
| void [Encrypt](./encrypt/)() | NOT IMPLEMENTED. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Constrói uma nova instância da classe [FileInfo](./) que representa o arquivo especificado. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Não faz nada. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Retorna os atributos da entidade representada pelo objeto atual. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Retorna a hora de criação da entidade representada pelo objeto atual como hora local. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Retorna a hora de criação da entidade representada pelo objeto atual como hora UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Retorna um objeto [DirectoryInfo](../directoryinfo/) que representa o diretório onde o arquivo representado pelo objeto atual está localizado. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Retorna o nome completo do diretório onde o arquivo representado pelo objeto atual está localizado. |
| **bool** [get_Exists](./get_exists/)() override | Retorna um valor que indica se o arquivo existe. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Retorna a extensão do arquivo representado pelo objeto atual. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Retorna o nome completo (incluindo caminho) da entidade representada pelo objeto atual. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Retorna um valor que indica se o atributo ReadOnly está definido. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Retorna a última hora de acesso da entidade representada pelo objeto atual como hora local. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Retorna a última hora de acesso da entidade representada pelo objeto atual como hora UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Retorna a última hora de gravação da entidade representada pelo objeto atual como hora local. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Retorna a última hora de gravação da entidade representada pelo objeto atual como hora UTC. |
| **int64_t** [get_Length](./get_length/)() | Retorna o tamanho do arquivo em bytes. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retorna o nome do arquivo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Move o arquivo representado pelo objeto atual para o local especificado. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de subclasses por cópia. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Abre o arquivo representado pelo objeto atual no modo especificado para leitura e escrita sem compartilhamento. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Abre o arquivo representado pelo objeto atual no modo especificado, com o tipo de acesso especificado e sem compartilhamento. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Abre o arquivo representado pelo objeto atual no modo especificado, com o tipo de acesso especificado e a opção de compartilhamento. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Abre um arquivo representado pelo objeto atual apenas para leitura, no modo 'Open' com acesso compartilhado para leitura. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Abre o arquivo existente no local especificado pelo caminho representado pelo objeto atual para leitura de texto usando codificação UTF-8 sem compartilhamento. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Abre um arquivo representado pelo objeto atual apenas para escrita, no modo 'OpenOrCreate' sem compartilhamento. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de subclasses por cópia. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| void [Refresh](../filesysteminfo/refresh/)() | Atualiza o estado do objeto atual. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Substitui o conteúdo de um arquivo de destino especificado pelo arquivo representado pelo objeto [FileInfo](./) atual e cria um backup do arquivo substituído. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Substitui o conteúdo de um arquivo de destino especificado pelo arquivo representado pelo objeto [FileInfo](./) atual e cria um backup do arquivo substituído. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Define os atributos especificados na entidade representada pelo objeto atual. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Define a hora de criação da entidade representada pelo objeto atual como hora local. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Define a hora de criação da entidade representada pelo objeto atual como hora UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Define ou remove o atributo ReadOnly no arquivo. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Define a última hora de acesso da entidade representada pelo objeto atual como hora local. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Define a última hora de acesso da entidade representada pelo objeto atual como hora UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Define a última hora de gravação da entidade representada pelo objeto atual como hora local. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Define a última hora de gravação da entidade representada pelo objeto atual como hora UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retorna um caminho representado pelo objeto atual. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Ver Também

* Classe [FileSystemInfo](../filesysteminfo/)
* Espaço de nomes [System::IO](../)
* Library [Aspose.Slides](../../)