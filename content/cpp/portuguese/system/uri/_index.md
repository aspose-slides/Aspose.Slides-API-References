---
title: Uri
second_title: Referência da API Aspose.Slides para C++
description: "Identificador de recurso unificado. Objetos desta classe devem ser alocados somente usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 1392
url: /pt/system/uri/
---
## Uri classe

Identificador de recurso uniforme. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class Uri : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Determina o tipo do nome de host especificado. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Determina se o esquema especificado é válido. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Compara os objetos [Uri](./) especificados usando as regras de comparação especificadas. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Determina se os URIs representados pelos objetos atual e especificado são iguais. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Converte uma string para sua representação escapada. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Converte uma string URI para sua representação escapada. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Obtém o valor decimal de um dígito hexadecimal. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Retorna o caminho absoluto do URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Retorna o URI absoluto. |
| [String](../string/) [get_Authority](./get_authority/)() const | Retorna o nome do host e o número da porta para um servidor. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Retorna um nome de host não escapado. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Retorna o fragmento de URI escapado. |
| [String](../string/) [get_Host](./get_host/)() const | Retorna o nome do host. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Retorna o tipo do nome do host. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Retorna um Nome de Domínio Internacional do host. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Determina se o URI representado pelo objeto atual é absoluto. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Determina se o URI representado pelo objeto atual tem a porta padrão para o esquema do URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Determina se o URI representado pelo objeto atual é um arquivo. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Determina se o URI representado pelo objeto atual referencia um host local. |
| **bool** [get_IsUnc](./get_isunc/)() const | Determina se o URI representado pelo objeto atual é um caminho UNC. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Retorna a representação do sistema operacional do nome de arquivo referenciado pelo URI representado pelo objeto atual. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Retorna a string URI que foi passada ao construtor quando o objeto atual foi construído. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Retorna o caminho absoluto e os componentes de consulta do URI representado pelo objeto atual, separados por um ponto de interrogação (?). |
| **int32_t** [get_Port](./get_port/)() const | Retorna o número da porta do URI representado pelo objeto atual. |
| [String](../string/) [get_Query](./get_query/)() const | Retorna as informações de consulta incluídas no URI representado pelo objeto atual. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Retorna o esquema do URI representado pelo objeto atual. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Retorna um array de strings contendo os segmentos de caminho do URI representado pelo objeto atual. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Determina se a string URI passada ao construtor do objeto atual estava totalmente escapada. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Retorna o nome de usuário, senha e outras informações de usuário associadas ao URI representado pelo objeto atual. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Retorna os componentes especificados do URI representado pelo objeto atual usando o escape especificado. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Obtém o código hash para o URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Retorna a porção especificada do URI representado pelo objeto atual. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Retorna o equivalente hexadecimal do caractere especificado. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Converte a representação hexadecimal especificada de um caractere para um caractere. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Determina se o URI representado pelo objeto [Uri](./) atual é a base do URI representado pelo objeto [Uri](./) especificado. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Determina se o caractere especificado representa um dígito hexadecimal válido. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Determina se um caractere na string especificada na posição especificada está codificado em hexadecimal. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indica se a string usada para construir este [Uri](./) estava bem formada e não precisa ser escapada adicionalmente. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Determina se a string especificada é um URI bem formado. |
| void [Lock](../object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Determina a diferença entre duas instâncias [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Determina a diferença entre os URIs representados pelo objeto atual e pelos objetos [Uri](./) especificados. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Retorna a representação em string do URI representado pelo objeto atual. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Constrói um objeto [Uri](./) que representa o URI especificado; um argumento especifica o tipo de URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Constrai um objeto [Uri](./) a partir do objeto [Uri](./) especificado que representa o URI base e a representação em string do URI relativo. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Constrói um objeto [Uri](./) a partir dos URIs base e relativo especificados. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa a construção C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Desfaz o escape da string escapada especificada. |
| void [Unlock](../object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
|  [Uri](./uri/)(const [String](../string/)\&) | Constrói um objeto [Uri](./) que representa o URI especificado. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Constrói um objeto [Uri](./) que representa o URI especificado; um argumento especifica se o URI deve ser escapado. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Constrói um objeto [Uri](./) a partir do objeto [Uri](./) especificado que representa o URI base e a representação em string do URI relativo; um argumento especifica se o URI deve ser escapado. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Constrói um objeto [Uri](./) que representa o URI especificado; um argumento especifica o tipo de URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Constrói um objeto [Uri](./) a partir dos URIs base e relativo especificados. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Constrói um objeto [Uri](./) a partir dos URIs base e relativo especificados. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Especifica os caracteres que separam o esquema do protocolo de comunicação da parte de endereço do [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Especifica que o [Uri](./) é um ponteiro para um arquivo. |
| static [UriSchemeFtp](./urischemeftp/) | Especifica que o [Uri](./) é acessado através do Protocolo de Transferência de Arquivos. |
| static [UriSchemeGopher](./urischemegopher/) | Especifica que o [Uri](./) é acessado através do protocolo Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Especifica que o [Uri](./) é acessado através do Protocolo de Transferência de Hipertexto. |
| static [UriSchemeHttps](./urischemehttps/) | Especifica que o [Uri](./) é acessado através do Protocolo Seguro de Transferência de Hipertexto. |
| static [UriSchemeMailto](./urischememailto/) | Especifica que o [Uri](./) é um endereço de e-mail e é acessado através do Protocolo de Transporte de Correio Simples. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Especifica que o [Uri](./) é acessado através do esquema NetPipe usado pelo [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Especifica que o [Uri](./) é acessado através do esquema NetTcp usado pelo [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Especifica que o [Uri](./) é um grupo de notícias da Internet e é acessado através do Protocolo de Transporte de Notícias de Rede. |
| static [UriSchemeNntp](./urischemenntp/) | Especifica que o [Uri](./) é um grupo de notícias da Internet e é acessado através do Protocolo de Transporte de Notícias de Rede. |

## Observações

```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## Veja também

* Classe [Object](../object/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)