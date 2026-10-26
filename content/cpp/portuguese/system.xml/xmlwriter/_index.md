---
title: XmlWriter
second_title: Referência da API Aspose.Slides para C++
description: Representa um escritor que fornece uma forma rápida, não em cache e somente avançada para gerar fluxos ou arquivos que contêm dados XML.
type: docs
weight: 573
url: /pt/system.xml/xmlwriter/
---
## XmlWriter classe

Representa um escritor que fornece uma forma rápida, não em cache e somente avançada para gerar fluxos ou arquivos que contêm dados XML.

```cpp
class XmlWriter : public System::IDisposable
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual void [Close](./close/)() | Quando sobrescrito em uma classe derivada, fecha este fluxo e o fluxo subjacente. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Cria uma nova instância [XmlWriter](./) usando o nome de arquivo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância [XmlWriter](./) usando o nome de arquivo e o objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Cria uma nova instância [XmlWriter](./) usando o fluxo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância [XmlWriter](./) usando o fluxo e o objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Cria uma nova instância [XmlWriter](./) usando o TextWriter especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância [XmlWriter](./) usando o TextWriter e os objetos [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Cria uma nova instância [XmlWriter](./) usando o [Text::StringBuilder](../../system.text/stringbuilder/) especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância [XmlWriter](./) usando os objetos [Text::StringBuilder](../../system.text/stringbuilder/) e [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Cria uma nova instância [XmlWriter](./) usando o objeto [XmlWriter](./) especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância [XmlWriter](./) usando os objetos [XmlWriter](./) e [XmlWriterSettings](../xmlwritersettings/) especificados. |
| void [Dispose](./dispose/)() override | Libera todos os recursos usados pela instância atual da classe [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual void [Flush](./flush/)() | Quando sobrescrito em uma classe derivada, envia todo o conteúdo do buffer para os fluxos subjacentes e também envia o fluxo subjacente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Retorna o objeto [XmlWriterSettings](../xmlwritersettings/) usado para criar esta instância [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Quando sobrescrito em uma classe derivada, obtém o estado do escritor. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Quando sobrescrito em uma classe derivada, obtém o escopo atual **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Quando sobrescrito em uma classe derivada, obtém um XmlSpace que representa o escopo atual **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite a geração de hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, retorna o prefixo mais próximo definido no escopo de namespace atual para o URI do namespace. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Quando sobrescrito em uma classe derivada, grava todos os atributos encontrados na posição atual em [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava um atributo com o nome local, URI de namespace e valor especificados. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o atributo com o nome local e valor especificados. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o atributo com o prefixo, nome local, URI de namespace e valor especificados. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Quando sobrescrito em uma classe derivada, codifica os bytes binários especificados como Base64 e grava o texto resultante. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Quando sobrescrito em uma classe derivada, codifica os bytes binários especificados como **BinHex** e grava o texto resultante. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, grava um bloco **...** contendo o texto especificado. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Quando sobrescrito em uma classe derivada, força a geração de uma entidade de caractere para o valor Unicode especificado. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Quando sobrescrito em uma classe derivada, grava texto um buffer por vez. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, grava um comentário **** contendo o texto especificado. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava a declaração DOCTYPE com o nome especificado e atributos opcionais. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Grava um elemento com o nome local e valor especificados. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Grava um elemento com o nome local, URI de namespace e valor especificados. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Grava um elemento com o prefixo, nome local, URI de namespace e valor especificados. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Quando sobrescrito em uma classe derivada, fecha a chamada anterior XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | Quando sobrescrito em uma classe derivada, fecha quaisquer elementos ou atributos abertos e devolve o escritor ao estado Start. |
| virtual void [WriteEndElement](./writeendelement/)() | Quando sobrescrito em uma classe derivada, fecha um elemento e remove o escopo de namespace correspondente. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava uma referência de entidade como **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Quando sobrescrito em uma classe derivada, fecha um elemento e remove o escopo de namespace correspondente. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o nome especificado, garantindo que seja um nome válido de acordo com a recomendação W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o nome especificado, garantindo que seja um NmToken válido de acordo com a recomendação W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Quando sobrescrito em uma classe derivada, copia tudo do leitor para o escritor e move o leitor para o início do próximo irmão. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copia tudo do objeto XPathNavigator para o escritor. A posição do XPathNavigator permanece inalterada. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Quando sobrescrito em uma classe derivada, grava uma instrução de processamento com um espaço entre o nome e o texto da seguinte forma: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o nome qualificado por namespace. Este método procura o prefixo que está em escopo para o namespace fornecido. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Quando sobrescrito em uma classe derivada, grava marcação bruta manualmente a partir de um buffer de caracteres. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava marcação bruta manualmente a partir de uma string. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Grava o início de um atributo com o nome local e URI de namespace especificados. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o início de um atributo com o prefixo, nome local e URI de namespace especificados. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Grava o início de um atributo com o nome local especificado. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Quando sobrescrito em uma classe derivada, grava a declaração XML com a versão "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Quando sobrescrito em uma classe derivada, grava a declaração XML com a versão "1.0" e o atributo standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava a tag de início especificada e a associa ao namespace fornecido. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava a tag de início especificada e a associa ao namespace e prefixo fornecidos. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava uma tag de início com o nome local especificado. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o conteúdo de texto fornecido. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Quando sobrescrito em uma classe derivada, gera e grava a entidade de caractere substituto para o par de caracteres substitutos. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Grava o valor do objeto. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Grava um valor [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Grava um valor [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Grava um valor [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Grava um valor [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Grava um valor [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Grava um número de ponto flutuante de precisão simples. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Grava um valor [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Grava um valor [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Grava um valor [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Quando sobrescrito em uma classe derivada, grava o espaço em branco fornecido. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado a uma instância desta classe. |

## Veja Também

* Classe [IDisposable](../../system/idisposable/)
* Espaço de nomes [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)