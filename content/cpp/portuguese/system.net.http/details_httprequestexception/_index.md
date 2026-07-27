---
title: Details_HttpRequestException
second_title: Referência da API Aspose.Slides para C++
description: "A classe de exceção base é lançada pelas classes HttpClient e HttpMessageHandler. Nunca crie instâncias desta classe manualmente. Use a classe HttpRequestException em vez disso. Nunca envolva as instâncias da classe HttpRequestException em System::SmartPtr."
type: docs
weight: 14
url: /pt/system.net.http/details_httprequestexception/
---
## Details_HttpRequestException classe


A classe de exceção base é lançada pelas [HttpClient](../httpclient/) e [HttpMessageHandler](../httpmessagehandler/) classes. Nunca crie instâncias desta classe manualmente. Use a classe HttpRequestException em vez disso. Nunca envolva as instâncias da classe HttpRequestException em [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_HttpRequestException : public System::Details_Exception
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [Details_HttpRequestException](./details_httprequestexception/)() | Constrói uma nova instância. |
|  [Details_HttpRequestException](./details_httprequestexception/)(std::nullptr_t) | Constrói uma nova instância. |
|  [Details_HttpRequestException](./details_httprequestexception/)([String](../../system/string/)) | Constrói uma nova instância. |
|  [Details_HttpRequestException](./details_httprequestexception/)([String](../../system/string/), [Exception](../../system/exception/)) | Constrói uma nova instância. |
| virtual void [DoThrow](../../system/details_exception/dothrow/)(const [ExceptionPtr](../../system/exceptionptr/)\&) const | Lança a instância de exceção envolvida pelo wrapper de exceção. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Retorna um dicionário com dados de exceção personalizados. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Retorna um valor inteiro de 32 bits que é um código HRESULT associado à exceção representada pelo objeto atual. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Retorna uma referência ao objeto que representa a exceção interna. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Retorna a string contendo a descrição do erro. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Retorna a string contendo o rastreamento de pilha. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Retorna a cópia do objeto Exception que representa a exceção mais interna. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite o hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite construir cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite construir cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Define o HRESULT, um valor numérico codificado que é atribuído a uma exceção específica. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Retorna a representação em string do objeto atual. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementa o método [what()](../../system/details_exception/what/) que é chamado pela classe [ExceptionWrapper](../../system/exceptionwrapper/). Apesar de o fato de que esta classe não herda de std::exception, classes derivadas podem usar membros protegidos/privados para implementar sua lógica. Mover a implementação deste método para o [ExceptionWrapper](../../system/exceptionwrapper/) pode quebrar essa lógica. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Tipos definidos

| Tipo definido | Descrição |
| --- | --- |
| [BaseType](./basetype/) |  |

## Veja também

* Classe [Details_Exception](../../system/details_exception/)
* Espaço de nomes [System::Net::Http](../)
* Biblioteca [Aspose.Slides](../../)