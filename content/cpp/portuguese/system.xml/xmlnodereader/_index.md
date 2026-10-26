---
title: XmlNodeReader
second_title: Referência da API Aspose.Slides para C++
description: Representa um leitor que fornece acesso rápido, sem cache, somente avançado, aos dados XML em um XmlNode.
type: docs
weight: 365
url: /pt/system.xml/xmlnodereader/
---
## XmlNodeReader classe

Representa um leitor que fornece acesso rápido, não armazenado em cache e somente avançado a dados XML em um [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [Close](./close/)() override | Altera o [XmlNodeReader::get_ReadState](./get_readstate/) para [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Cria uma nova instância [XmlReader](../xmlreader/) com a URI especificada. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando a URI e as configurações especificadas. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando a URI, as configurações e as informações de contexto especificadas para a análise. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando o fluxo especificado com configurações padrão. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Cria uma nova instância [XmlReader](../xmlreader/) com o fluxo e as configurações especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando o fluxo especificado, a URI base e as configurações. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando o fluxo especificado, as configurações e as informações de contexto para a análise. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando o leitor de texto especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando o leitor de texto e as configurações especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando o leitor de texto, as configurações e a URI base especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Cria uma nova instância [XmlReader](../xmlreader/) usando o leitor de texto, as configurações e as informações de contexto para a análise. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Cria uma nova instância [XmlReader](../xmlreader/) usando o leitor XML e as configurações especificados. |
| void [Dispose](../xmlreader/dispose/)() override | Libera todos os recursos usados pela instância atual da classe [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaN são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaN são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Retorna o número de atributos no nó atual. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Retorna a URI base do nó atual. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Retorna um valor que indica se [XmlNodeReader](./) implementa os métodos de leitura de conteúdo binário. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Retorna um valor que indica se [XmlReader](../xmlreader/) implementa o método [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Retorna um valor que indica se este leitor pode analisar e resolver entidades. |
| **int32_t** [get_Depth](./get_depth/)() override | Retorna a profundidade do nó atual no documento XML. |
| **bool** [get_EOF](./get_eof/)() override | Retorna um valor que indica se o leitor está posicionado no final do fluxo. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Retorna um valor que indica se o nó atual possui atributos. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Retorna um valor que indica se o nó atual pode ter um valor [XmlNodeReader::get_Value](./get_value/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Retorna um valor que indica se o nó atual é um atributo gerado a partir do valor padrão definido na definição de tipo de documento (DTD) ou no esquema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Retorna um valor que indica se o nó atual é um elemento vazio (por exemplo, **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Retorna o nome local do nó atual. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retorna o nome qualificado do nó atual. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Retorna o URI do namespace (conforme definido na especificação de Namespaces da W3C) do nó no qual o leitor está posicionado. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Retorna o [XmlNameTable](../xmlnametable/) associado a esta implementação. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Retorna o tipo do nó atual. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Retorna o prefixo do namespace associado ao nó atual. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Quando sobrescrito em uma classe derivada, obtém o caractere de aspas usado para envolver o valor de um nó de atributo. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Retorna o estado do leitor. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Retorna as informações de esquema que foram atribuídas ao nó atual. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Retorna o objeto [XmlReaderSettings](../xmlreadersettings/) usado para criar esta instância [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Retorna o valor de texto do nó atual. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Retorna o tipo do nó atual. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Retorna o escopo atual **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Retorna o escopo atual **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Retorna o valor do atributo com o nome especificado. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Retorna o valor do atributo com o nome local e URI do namespace especificados. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Retorna o valor do atributo com o índice especificado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permite a hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com o índice especificado. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com o valor [XmlReader::get_Name](../xmlreader/get_name/) especificado. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com os valores [XmlReader::get_LocalName](../xmlreader/get_localname/) e [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) especificados. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador 'is' de C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Retorna um valor que indica se o argumento string é um nome XML válido. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Retorna um valor que indica se o argumento string é um token de nome XML válido. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Chama [XmlReader::MoveToContent](../xmlreader/movetocontent/) e verifica se o nó de conteúdo atual é uma tag de início ou uma tag de elemento vazio. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Chama [XmlReader::MoveToContent](../xmlreader/movetocontent/) e verifica se o nó de conteúdo atual é uma tag de início ou uma tag de elemento vazio e se o valor [XmlReader::get_Name](../xmlreader/get_name/) do elemento encontrado corresponde ao argumento fornecido. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Chama [XmlReader::MoveToContent](../xmlreader/movetocontent/) e verifica se o nó de conteúdo atual é uma tag de início ou uma tag de elemento vazio e se os valores [XmlReader::get_LocalName](../xmlreader/get_localname/) e [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) do elemento encontrado correspondem às strings fornecidas. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Resolve um prefixo de namespace no escopo do elemento atual. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Move para o atributo com o nome especificado. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Move para o atributo com o nome local e o URI do namespace especificados. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Move para o atributo com o índice especificado. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Verifica se o nó atual é um nó de conteúdo (texto não-espaço em branco, **CDATA**, **Element**, **EndElement**, **EntityReference** ou **EndEntity**). Se o nó não for um nó de conteúdo, o leitor avança para o próximo nó de conteúdo ou para o fim do arquivo. Ele ignora nós dos seguintes tipos: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** ou **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Move para o elemento que contém o nó de atributo atual. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Move para o primeiro atributo. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Move para o próximo atributo. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, realmente, apenas inicializa um novo objeto e permite a construção de cópias das subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, realmente, apenas inicializa um novo objeto e permite a construção de cópias das subclasses. |
| **bool** [Read](./read/)() override | Lê o próximo nó do fluxo. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Analisa o valor do atributo em um ou mais nós **[Text](../../system.text/)**, **EntityReference** ou **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lê o conteúdo como um objeto do tipo especificado. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lê o conteúdo e devolve os bytes binários decodificados em Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lê o conteúdo e devolve os bytes binários decodificados em BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Lê o conteúdo de texto na posição atual como um [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Lê o conteúdo de texto na posição atual como um objeto [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Lê o conteúdo de texto na posição atual como um objeto [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Lê o conteúdo de texto na posição atual como um objeto [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Lê o conteúdo de texto na posição atual como um número de ponto flutuante de dupla precisão. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Lê o conteúdo de texto na posição atual como um número de ponto flutuante de precisão simples. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Lê o conteúdo de texto na posição atual como um inteiro assinado de 32 bits. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Lê o conteúdo de texto na posição atual como um inteiro assinado de 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Lê o conteúdo de texto na posição atual como um [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Lê o conteúdo de texto na posição atual como um objeto [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lê o conteúdo do elemento como o tipo solicitado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o conteúdo do elemento como o tipo solicitado. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lê o elemento e decodifica o conteúdo Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Lê o elemento e decodifica o conteúdo BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Lê o elemento atual e retorna o conteúdo como um objeto [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um objeto [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Lê o elemento atual e retorna o conteúdo como um objeto [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um objeto [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um objeto [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um objeto [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Lê o elemento atual e retorna o conteúdo como um número de ponto flutuante de precisão dupla. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um número de ponto flutuante de precisão dupla. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Lê o elemento atual e retorna o conteúdo como um número de ponto flutuante de precisão simples. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um número de ponto flutuante de precisão simples. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Lê o elemento atual e retorna o conteúdo como um inteiro assinado de 32 bits. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um inteiro assinado de 32 bits. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Lê o elemento atual e retorna o conteúdo como um inteiro assinado de 64 bits. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um inteiro assinado de 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Lê o elemento atual e retorna o conteúdo como um [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Lê o elemento atual e retorna o conteúdo como um objeto [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e retorna o conteúdo como um objeto [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Lê um elemento apenas de texto. No entanto, recomenda-se usar o método [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) em vez disso, pois ele fornece uma forma mais direta de lidar com esta operação. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Verifica se o valor [XmlReader::get_Name](../xmlreader/get_name/) do elemento encontrado corresponde à string fornecida antes de ler um elemento apenas de texto. No entanto, recomenda-se usar o método [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) em vez disso, pois ele fornece uma forma mais direta de lidar com esta operação. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Verifica se os valores [XmlReader::get_LocalName](../xmlreader/get_localname/) e [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) do elemento encontrado correspondem às strings fornecidas antes de ler um elemento apenas de texto. No entanto, recomenda-se usar o método [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) em vez disso, pois ele fornece uma forma mais direta de lidar com esta operação. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Verifica se o nó de conteúdo atual é uma tag de fechamento e avança o leitor para o próximo nó. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Quando sobrescrito em uma classe derivada, lê todo o conteúdo, incluindo marcação, como uma string. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Quando sobrescrito em uma classe derivada, lê o conteúdo, incluindo marcação, que representa este nó e todos os seus filhos. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Verifica se o nó atual é um elemento e avança o leitor para o próximo nó. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Verifica se o nó de conteúdo atual é um elemento com o valor [XmlReader::get_Name](../xmlreader/get_name/) fornecido e avança o leitor para o próximo nó. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nó de conteúdo atual é um elemento com os valores [XmlReader::get_LocalName](../xmlreader/get_localname/) e [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) fornecidos e avança o leitor para o próximo nó. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Lê o conteúdo de um elemento ou nó de texto como uma string. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Retorna uma nova instância [XmlReader](../xmlreader/) que pode ser usada para ler o nó atual e todos os seus descendentes. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Avança o [XmlReader](../xmlreader/) para o próximo elemento descendente com o nome qualificado especificado. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Avança o [XmlReader](../xmlreader/) para o próximo elemento descendente com o nome local e o URI do namespace especificados. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Lê até que um elemento com o nome qualificado especificado seja encontrado. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Lê até que um elemento com o nome local e o URI do namespace especificados seja encontrado. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Avança o [XmlReader](../xmlreader/) para o próximo elemento irmão com o nome qualificado especificado. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Avança o [XmlReader](../xmlreader/) para o próximo elemento irmão com o nome local e o URI do namespace especificados. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Lê grandes fluxos de texto incorporados em um documento XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui a contagem de referência compartilhada pelo valor especificado. |
| void [ResolveEntity](./resolveentity/)() override | Resolve a referência de entidade para nós **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa a contagem de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna a contagem de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [Skip](./skip/)() override | Ignora os filhos do nó atual. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa a contagem de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa a contagem de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Cria uma instância da classe [XmlNodeReader](./) usando o [XmlNode](../xmlnode/) especificado. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
## Tipos Definidos

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado a uma instância desta classe. |
## Observações

Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo como argumento a funções. 

## Veja Também

* Classe [XmlReader](../xmlreader/)
* Classe [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Espaço de nomes [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)