---
title: Cookie
second_title: Referência da API Aspose.Slides para C++
description: "Representa um cookie HTTP. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo como argumento para funções."
type: docs
weight: 1
url: /pt/system.net/cookie/
---
## Classe Cookie

Representa um cookie HTTP. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class Cookie : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Cria uma cópia da instância atual. |
|  [Cookie](./cookie/)() | Constrói uma nova instância. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Constrói uma nova instância. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Constrói uma nova instância. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Constrói uma nova instância. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Obtém o valor do atributo 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Obtém o valor do atributo 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Obtém o valor do atributo 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Obtém o valor do atributo 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Obtém um valor que indica se o domínio é implícito. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Retorna a chave do domínio. |
| **bool** [get_Expired](./get_expired/)() | Obtém um valor que indica se o cookie expirou. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Obtém o valor do atributo 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Obtém o valor do atributo 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Obtém o nome do cookie. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Obtém o valor do atributo 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Retorna um valor que indica se a especificação do cookie é 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Obtém o valor do atributo 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Retorna a coleção dos valores do atributo 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Obtém o valor do atributo 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Retorna o horário em que o cookie foi criado. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Obtém o valor do cookie. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Obtém a especificação do cookie. |
| **int32_t** [get_Version](./get_version/)() const | Obtém o valor do atributo '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de contagem de referência associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite o hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Este método é chamado por outros métodos para definir um nome de método. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui a contagem de referência compartilhada pelo valor especificado. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Define o valor do atributo 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Define o valor do atributo 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Define o valor do atributo 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Define o valor do atributo 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Define um valor que indica se o domínio é implícito. |
| void [set_Expired](./set_expired/)(**bool**) | Define um valor que indica se o cookie expirou. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Define o valor do atributo 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Define o valor do atributo 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Define o nome do cookie. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Define o valor do atributo 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Define o valor do atributo 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Define o valor do atributo 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Define o valor do cookie. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Define a especificação do cookie. |
| void [set_Version](./set_version/)(**int32_t**) | Define o valor do atributo '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa a contagem de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna a contagem de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serializa a instância atual para a representação em string. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Verifica e define os valores dos atributos padrão. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa a contagem de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa a contagem de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | O nome do atributo 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | O nome do atributo 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | O nome do atributo 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | O nome do atributo 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | O separador usado para separar o nome e o valor de um atributo. |
| static [ExpiresAttributeName](./expiresattributename/) | O nome do atributo 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | O nome do atributo 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | O nome do atributo 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | A versão máxima suportada. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | A representação em string da versão máxima suportada. |
| static [PathAttributeName](./pathattributename/) | O nome do atributo 'Path'. |
| static [PortAttributeName](./portattributename/) | O nome do atributo 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | O array que contém delimitadores para os valores do atributo 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | O símbolo usado para envolver as partes do atributo. |
| static [ReservedToName](./reservedtoname/) | Um valor reservado para o nome do cookie. |
| static [ReservedToValue](./reservedtovalue/) | Um valor reservado para o valor do cookie. |
| static [SecureAttributeName](./secureattributename/) | O nome do atributo 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | O separador de atributos. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | O prefixo dos nomes dos atributos especiais. |
| static [VersionAttributeName](./versionattributename/) | O nome do atributo '[Version](../../system/version/)'. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Net](../)
* Biblioteca [Aspose.Slides](../../)