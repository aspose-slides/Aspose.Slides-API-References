---
title: FileSystemInfo
second_title: Referência da API Aspose.Slides para C++
description: "A classe base para FileInfo e DirectoryInfo. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 300
url: /pt/system.io/filesysteminfo/
---
## FileSystemInfo classe


A classe base para [FileInfo](../fileinfo/) e [DirectoryInfo](../directoryinfo/). Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class FileSystemInfo : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [Delete](./delete/)() | Exclui a entidade representada pelo objeto atual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual void [Finalize](./finalize/)() | Não faz nada. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | Retorna os atributos da entidade representada pelo objeto atual. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | Retorna a hora de criação da entidade representada pelo objeto atual como horário local. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | Retorna a hora de criação da entidade representada pelo objeto atual como horário UTC. |
| virtual **bool** [get_Exists](./get_exists/)() | Determina se a entidade referenciada pelo caminho representado pelo objeto atual existe. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | Retorna a extensão do arquivo representado pelo objeto atual. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | Retorna o nome completo (incluindo caminho) da entidade representada pelo objeto atual. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | Retorna a hora de último acesso da entidade representada pelo objeto atual como horário local. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Retorna a hora de último acesso da entidade representada pelo objeto atual como horário UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | Retorna a hora de última gravação da entidade representada pelo objeto atual como horário local. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Retorna a hora de última gravação da entidade representada pelo objeto atual como horário UTC. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Retorna um nome da entidade representada pelo objeto atual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite a hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da declaração C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| void [Refresh](./refresh/)() | Atualiza o estado do objeto atual. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | Define os atributos especificados na entidade representada pelo objeto atual. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | Define a hora de criação da entidade representada pelo objeto atual como horário local. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | Define a hora de criação da entidade representada pelo objeto atual como horário UTC. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | Define a hora de último acesso da entidade representada pelo objeto atual como horário local. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Define a hora de último acesso da entidade representada pelo objeto atual como horário UTC. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | Define a hora de última gravação da entidade representada pelo objeto atual como horário local. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Define a hora de última gravação da entidade representada pelo objeto atual como horário UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamada diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamada diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da declaração C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamada diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamada diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)