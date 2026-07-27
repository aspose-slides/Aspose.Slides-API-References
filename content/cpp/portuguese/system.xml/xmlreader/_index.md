---
title: XmlReader
second_title: Referência da API Aspose.Slides para C++
description: Representa um leitor que fornece acesso rápido, sem cache, somente avançado a dados XML.
type: docs
weight: 430
url: /pt/system.xml/xmlreader/
---
## XmlReader classe

Representa um leitor que fornece acesso rápido, sem cache e somente avançado aos dados XML.

```cpp
class XmlReader : public System::IDisposable
```

## Métodos

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Quando sobrescrito em uma classe derivada, altera o [XmlReader::get_ReadState](./get_readstate/) para [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Cria uma nova instância [XmlReader](./) com o URI especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Cria uma nova instância [XmlReader](./) usando o URI e as configurações especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Cria uma nova instância [XmlReader](./) usando o URI, as configurações e as informações de contexto especificadas para análise. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Cria uma nova instância [XmlReader](./) usando o fluxo especificado com as configurações padrão. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Cria uma nova instância [XmlReader](./) com o fluxo e as configurações especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Cria uma nova instância [XmlReader](./) usando o fluxo, o URI base e as configurações especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Cria uma nova instância [XmlReader](./) usando o fluxo, as configurações e as informações de contexto especificados para análise. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Cria uma nova instância [XmlReader](./) usando o leitor de texto especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Cria uma nova instância [XmlReader](./) usando o leitor de texto e as configurações especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Cria uma nova instância [XmlReader](./) usando o leitor de texto, as configurações e o URI base especificados. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Cria uma nova instância [XmlReader](./) usando o leitor de texto, as configurações e as informações de contexto especificados para análise. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Cria uma nova instância [XmlReader](./) usando o leitor XML e as configurações especificados. |
| void [Dispose](./dispose/)() override | Libera todos os recursos usados pela instância atual da classe [XmlReader](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | Quando sobrescrito em uma classe derivada, obtém o número de atributos no nó atual. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Quando sobrescrito em uma classe derivada, obtém o URI base do nó atual. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Retorna um valor indicando se o [XmlReader](./) implementa os métodos de leitura de conteúdo binário. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Retorna um valor indicando se o [XmlReader](./) implementa o método [XmlReader::ReadValueChunk](./readvaluechunk/). |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | Retorna um valor indicando se este leitor pode analisar e resolver entidades. |
| virtual **int32_t** [get_Depth](./get_depth/)() | Quando sobrescrito em uma classe derivada, obtém a profundidade do nó atual no documento XML. |
| virtual **bool** [get_EOF](./get_eof/)() | Quando sobrescrito em uma classe derivada, obtém um valor indicando se o leitor está posicionado ao final do fluxo. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Retorna um valor indicando se o nó atual possui atributos. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | Quando sobrescrito em uma classe derivada, obtém um valor indicando se o nó atual pode ter um valor [XmlReader::get_Value](./get_value/). |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | Quando sobrescrito em uma classe derivada, obtém um valor indicando se o nó atual é um atributo gerado a partir do valor padrão definido no DTD ou schema. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Quando sobrescrito em uma classe derivada, obtém um valor indicando se o nó atual é um elemento vazio (por exemplo, **<MyElement/>**). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Quando sobrescrito em uma classe derivada, obtém o nome local do nó atual. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Quando sobrescrito em uma classe derivada, obtém o nome qualificado do nó atual. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Quando sobrescrito em uma classe derivada, obtém o URI do namespace (conforme definido na especificação de Namespace da W3C) do nó onde o leitor está posicionado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Quando sobrescrito em uma classe derivada, obtém o [XmlNameTable](../xmlnametable/) associado a esta implementação. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | Quando sobrescrito em uma classe derivada, obtém o tipo do nó atual. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Quando sobrescrito em uma classe derivada, obtém o prefixo de namespace associado ao nó atual. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | Quando sobrescrito em uma classe derivada, obtém o caractere de aspas usado para delimitar o valor de um nó de atributo. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | Quando sobrescrito em uma classe derivada, obtém o estado do leitor. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Retorna as informações de esquema que foram atribuídas ao nó atual como resultado da validação de esquema. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | Retorna o objeto [XmlReaderSettings](../xmlreadersettings/) usado para criar esta instância [XmlReader](./). |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | Quando sobrescrito em uma classe derivada, obtém o valor de texto do nó atual. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Retorna o tipo do nó atual. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Quando sobrescrito em uma classe derivada, obtém o escopo **xml:lang** atual. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Quando sobrescrito em uma classe derivada, obtém o escopo **xml:space** atual. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com o valor [XmlReader::get_Name](./get_name/) especificado. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com os valores [XmlReader::get_LocalName](./get_localname/) e [XmlReader::get_NamespaceURI](./get_namespaceuri/) especificados. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com o índice especificado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite a hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com o índice especificado. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com o valor [XmlReader::get_Name](./get_name/) especificado. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | Quando sobrescrito em uma classe derivada, obtém o valor do atributo com os valores [XmlReader::get_LocalName](./get_localname/) e [XmlReader::get_NamespaceURI](./get_namespaceuri/) especificados. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador 'is' do C#. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | Retorna um valor indicando se o argumento string é um nome XML válido. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | Retorna um valor indicando se o argumento string é um token de nome XML válido. |
| virtual **bool** [IsStartElement](./isstartelement/)() | Chama [XmlReader::MoveToContent](./movetocontent/) e testa se o nó de conteúdo atual é uma tag de início ou tag de elemento vazio. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | Chama [XmlReader::MoveToContent](./movetocontent/) e testa se o nó de conteúdo atual é uma tag de início ou tag de elemento vazio e se o valor [XmlReader::get_Name](./get_name/) do elemento encontrado corresponde ao argumento fornecido. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Chama [XmlReader::MoveToContent](./movetocontent/) e testa se o nó de conteúdo atual é uma tag de início ou tag de elemento vazio e se os valores [XmlReader::get_LocalName](./get_localname/) e [XmlReader::get_NamespaceURI](./get_namespaceuri/) do elemento encontrado correspondem às strings fornecidas. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, resolve um prefixo de namespace no escopo do elemento atual. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonar tipos personalizados. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, move para o atributo com o valor [XmlReader::get_Name](./get_name/) especificado. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Quando sobrescrito em uma classe derivada, move para o atributo com os valores [XmlReader::get_LocalName](./get_localname/) e [XmlReader::get_NamespaceURI](./get_namespaceuri/) especificados. |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | Quando sobrescrito em uma classe derivada, move para o atributo com o índice especificado. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | Verifica se o nó atual é um nó de conteúdo (texto não-espaço em branco, **CDATA**, **Element**, **EndElement**, **EntityReference** ou **EndEntity**). Se o nó não for um nó de conteúdo, o leitor avança para o próximo nó de conteúdo ou fim do arquivo. Ele ignora nós dos seguintes tipos: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ou **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | Quando sobrescrito em uma classe derivada, move para o elemento que contém o nó de atributo atual. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Quando sobrescrito em uma classe derivada, move para o primeiro atributo. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Quando sobrescrito em uma classe derivada, move para o próximo atributo. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópias de subclasses. |
| virtual **bool** [Read](./read/)() | Quando sobrescrito em uma classe derivada, lê o próximo nó do fluxo. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | Quando sobrescrito em uma classe derivada, analisa o valor do atributo em um ou mais nós **[Text](../../system.text/)**, **EntityReference** ou **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lê o conteúdo como um objeto do tipo especificado. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Lê o conteúdo e retorna os bytes binários decodificados em Base64. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Lê o conteúdo e retorna os bytes binários decodificados em **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | Lê o conteúdo de texto na posição atual como um [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | Lê o conteúdo de texto na posição atual como um objeto [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Lê o conteúdo de texto na posição atual como um objeto [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | Lê o conteúdo de texto na posição atual como um objeto [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | Lê o conteúdo de texto na posição atual como um número de ponto flutuante de dupla precisão. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | Lê o conteúdo de texto na posição atual como um número de ponto flutuante de precisão simples. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | Lê o conteúdo de texto na posição atual como um inteiro assinado de 32 bits. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | Lê o conteúdo de texto na posição atual como um inteiro assinado de 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | Lê o conteúdo de texto na posição atual como um [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | Lê o conteúdo de texto na posição atual como um objeto [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Lê o conteúdo do elemento como o tipo solicitado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o conteúdo do elemento como o tipo solicitado. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Lê o elemento e decodifica o conteúdo **Base64**. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Lê o elemento e decodifica o conteúdo **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Lê o elemento atual e devolve o conteúdo como um objeto [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um objeto [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Lê o elemento atual e devolve o conteúdo como um objeto [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um objeto [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Lê o elemento atual e devolve o conteúdo como um objeto [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um objeto [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Lê o elemento atual e devolve o conteúdo como um número de ponto flutuante de dupla precisão. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um número de ponto flutuante de dupla precisão. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Lê o elemento atual e devolve o conteúdo como um número de ponto flutuante de precisão simples. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um número de ponto flutuante de precisão simples. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | Lê o elemento atual e devolve o conteúdo como um inteiro assinado de 32 bits. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um inteiro assinado de 32 bits. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | Lê o elemento atual e devolve o conteúdo como um inteiro assinado de 64 bits. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um inteiro assinado de 64 bits. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | Lê o elemento atual e devolve o conteúdo como um [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | Lê o elemento atual e devolve o conteúdo como um objeto [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nome local e o URI do namespace especificados correspondem aos do elemento atual, então lê o elemento atual e devolve o conteúdo como um objeto [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | Lê um elemento apenas de texto. Contudo, recomenda-se usar o método [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) em vez disso, pois ele fornece uma maneira mais direta de lidar com esta operação. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | Verifica se o valor [XmlReader::get_Name](./get_name/) do elemento encontrado corresponde à string fornecida antes de ler um elemento apenas de texto. Contudo, recomenda-se usar o método [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) em vez disso, pois ele fornece uma maneira mais direta de lidar com esta operação. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Verifica se os valores [XmlReader::get_LocalName](./get_localname/) e [XmlReader::get_NamespaceURI](./get_namespaceuri/) do elemento encontrado correspondem às strings fornecidas antes de ler um elemento apenas de texto. Contudo, recomenda-se usar o método [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) em vez disso, pois ele fornece uma maneira mais direta de lidar com esta operação. |
| virtual void [ReadEndElement](./readendelement/)() | Verifica se o nó de conteúdo atual é uma tag de fechamento e avança o leitor para o próximo nó. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | Quando sobrescrito em uma classe derivada, lê todo o conteúdo, incluindo marcação, como uma string. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | Quando sobrescrito em uma classe derivada, lê o conteúdo, incluindo marcação, que representa este nó e todos os seus filhos. |
| virtual void [ReadStartElement](./readstartelement/)() | Verifica se o nó atual é um elemento e avança o leitor para o próximo nó. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | Verifica se o nó de conteúdo atual é um elemento com o valor [XmlReader::get_Name](./get_name/) fornecido e avança o leitor para o próximo nó. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Verifica se o nó de conteúdo atual é um elemento com os valores [XmlReader::get_LocalName](./get_localname/) e [XmlReader::get_NamespaceURI](./get_namespaceuri/) fornecidos e avança o leitor para o próximo nó. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Quando sobrescrito em uma classe derivada, lê o conteúdo de um elemento ou nó de texto como uma string. Contudo, recomenda-se usar o método [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) em vez disso, pois ele fornece uma maneira mais direta de lidar com esta operação. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | Retorna uma nova instância [XmlReader](./) que pode ser usada para ler o nó atual e todos os seus descendentes. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | Avança o [XmlReader](./) para o próximo elemento descendente com o nome qualificado especificado. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Avança o [XmlReader](./) para o próximo elemento descendente com o nome local e URI de namespace especificados. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | Lê até que um elemento com o nome qualificado especificado seja encontrado. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Lê até que um elemento com o nome local e URI de namespace especificados seja encontrado. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | Avança o [XmlReader](./) para o próximo elemento irmão com o nome qualificado especificado. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Avança o [XmlReader](./) para o próximo elemento irmão com o nome local e URI de namespace especificados. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Lê grandes fluxos de texto incorporados em um documento XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui a contagem de referência compartilhada pelo valor especificado. |
| virtual void [ResolveEntity](./resolveentity/)() | Quando sobrescrito em uma classe derivada, resolve a referência de entidade para nós **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa a contagem de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve a contagem de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual void [Skip](./skip/)() | Ignora os filhos do nó atual. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa a contagem de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa a contagem de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Definições de tipo

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado a uma instância desta classe. |
## Veja Também

* Classe [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)