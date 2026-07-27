---
title: Details_ArgumentNullException
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 339
url: /pt/system/details_argumentnullexception/
---
## Details_ArgumentNullException classe




```cpp
class Details_ArgumentNullException : public System::Details_ArgumentException
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para fins internos. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Retorna dicionário com dados de exceção personalizados. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Retorna um valor inteiro de 32 bits que é um código HRESULT associado à exceção representada pelo objeto atual. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Retorna uma referência ao objeto que representa a exceção interna. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Retorna a string contendo a descrição do erro. |
| [String](../string/) [get_ParamName](./get_paramname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Retorna a string contendo o rastreamento da pilha. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Retorna a cópia do objeto Exception que representa a exceção mais interna. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Análogo do método C# [Object.GetHashCode()](../object/gethashcode/). Permite hash de objetos personalizados. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Obtém o tipo real do objeto. Análogo da chamada C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Análogo do método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Define HRESULT, um valor numérico codificado que é atribuído a uma exceção específica. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Retorna a representação em string do objeto atual. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementa o método [what()](../details_exception/what/) que é chamado pela classe [ExceptionWrapper](../exceptionwrapper/). Apesar do fato de que esta classe não herda de std::exception, classes derivadas podem usar membros protegidos/privados para implementar sua lógica. Mover a implementação deste método para o [ExceptionWrapper](../exceptionwrapper/) pode quebrar essa lógica. |
| virtual  [~Object](../object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [Details_ArgumentException](../details_argumentexception/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)