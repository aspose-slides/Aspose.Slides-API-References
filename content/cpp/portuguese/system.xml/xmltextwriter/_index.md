---
title: XmlTextWriter
second_title: Referência da API Aspose.Slides para C++
description: Representa um writer que fornece um modo rápido, não armazenado em cache e somente de avanço para gerar fluxos ou arquivos contendo dados XML que conformam com a Extensible Markup Language (XML) 1.0 da W3C e as recomendações Namespaces in XML.
type: docs
weight: 521
url: /pt/system.xml/xmltextwriter/
---
## Métodos


Representa um writer que fornece um modo rápido, não armazenado em cache e somente de avanço para gerar fluxos ou arquivos contendo dados XML que conformam com a Extensible Markup Language (XML) 1.0 da W3C e as recomendações Namespaces in XML.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Métodos

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Fecha este fluxo e o fluxo subjacente. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando o nome de arquivo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando o nome de arquivo e o objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando o stream especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando o stream e o objeto [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando o TextWriter especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando o TextWriter e os objetos [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando o [Text::StringBuilder](../../system.text/stringbuilder/) especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando os objetos [Text::StringBuilder](../../system.text/stringbuilder/) e [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando o objeto [XmlWriter](../xmlwriter/) especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Cria uma nova instância de [XmlWriter](../xmlwriter/) usando os objetos [XmlWriter](../xmlwriter/) e [XmlWriterSettings](../xmlwritersettings/) especificados. |
| void [Dispose](../xmlwriter/dispose/)() override | Libera todos os recursos usados pela instância atual da classe [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| void [Flush](./flush/)() override | Despeja tudo que está no buffer para os fluxos subjacentes e também despeja o fluxo subjacente. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Retorna o objeto de fluxo subjacente. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Indica como a saída é formatada. |
| **int32_t** [get_Indentation](./get_indentation/)() | Retorna quantos IndentChars escrever para cada nível na hierarquia quando [XmlTextWriter::set_Formatting](./set_formatting/) está definido como [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Retorna qual caractere usar para recuo quando [XmlTextWriter::set_Formatting](./set_formatting/) está definido como [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Retorna um valor indicando se deve suportar namespaces. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Retorna qual caractere usar para citar valores de atributos. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Retorna o objeto [XmlWriterSettings](../xmlwritersettings/) usado para criar esta instância [XmlWriter](../xmlwriter/). |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Retorna o estado do writer. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Retorna o escopo atual de **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Retorna um XmlSpace representando o escopo atual de **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Retorna o prefixo mais próximo definido no escopo de namespace atual para o URI do namespace. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência o objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Indica como a saída é formatada. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Define quantos IndentChars escrever para cada nível na hierarquia quando [XmlTextWriter::set_Formatting](./set_formatting/) está definido como [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Define qual caractere usar para recuo quando [XmlTextWriter::set_Formatting](./set_formatting/) está definido como [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Define um valor indicando se deve suportar namespaces. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Define qual caractere usar para citar valores de atributos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Quando sobrescrito em uma classe derivada, grava todos os atributos encontrados na posição atual em [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava um atributo com o nome local, URI de namespace e valor especificados. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o atributo com o nome local e valor especificados. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava o atributo com o prefixo, nome local, URI de namespace e valor especificados. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Codifica os bytes binários especificados como base64 e grava o texto resultante. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Codifica os bytes binários especificados como binhex e grava o texto resultante. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Grava um bloco **...** contendo o texto especificado. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Força a geração de uma entidade de caractere para o valor Unicode de caractere especificado. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Grava texto um buffer de cada vez. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Grava um comentário **** contendo o texto especificado. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Grava a declaração DOCTYPE com o nome especificado e atributos opcionais. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Grava um elemento com o nome local e valor especificados. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Grava um elemento com o nome local, URI de namespace e valor especificados. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Grava um elemento com o prefixo, nome local, URI de namespace e valor especificados. |
| void [WriteEndAttribute](./writeendattribute/)() override | Fecha a chamada [XmlTextWriter::WriteStartAttribute](./writestartattribute/) anterior. |
| void [WriteEndDocument](./writeenddocument/)() override | Fecha quaisquer elementos ou atributos abertos e devolve o escritor ao estado Start. |
| void [WriteEndElement](./writeendelement/)() override | Fecha um elemento e remove o escopo de namespace correspondente. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Grava uma referência de entidade como **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Fecha um elemento e remove o escopo de namespace correspondente. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Grava o nome especificado, garantindo que seja um nome válido de acordo com [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Grava o nome especificado, garantindo que seja um **NmToken** válido de acordo com [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Quando sobrescrito em uma classe derivada, copia tudo do leitor para o escritor e move o leitor para o início do próximo irmão. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Copia tudo do objeto XPathNavigator para o escritor. A posição do XPathNavigator permanece inalterada. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Grava uma instrução de processamento com um espaço entre o nome e o texto da seguinte forma: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Grava o nome qualificado por namespace. Este método procura o prefixo que está em escopo para o namespace fornecido. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Grava marcação bruta manualmente a partir de um buffer de caracteres. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Grava marcação bruta manualmente a partir de uma string. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Grava o início de um atributo. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Grava o início de um atributo com o nome local e URI de namespace especificados. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Grava o início de um atributo com o nome local especificado. |
| void [WriteStartDocument](./writestartdocument/)() override | Grava a declaração XML com a versão "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Grava a declaração XML com a versão "1.0" e o atributo standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Grava a tag inicial especificada e a associa ao namespace e prefixo fornecidos. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava a tag inicial especificada e a associa ao namespace fornecido. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Quando sobrescrito em uma classe derivada, grava uma tag inicial com o nome local especificado. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Grava o conteúdo de texto fornecido. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Gera e grava a entidade de caractere substituta para o par de caracteres substitutos. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Grava o valor do objeto. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Grava um valor [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Grava um valor [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Grava um valor [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Grava um valor [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Grava um valor [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Grava um número de ponto flutuante de precisão simples. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Grava um valor [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Grava um valor [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Grava um valor [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Grava o espaço em branco fornecido. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Cria uma instância da classe [XmlTextWriter](./) usando o stream e codificação especificados. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Cria uma instância da classe [XmlTextWriter](./) usando o arquivo especificado. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Cria uma instância da classe [XmlTextWriter](./) usando o TextWriter especificado. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Tipos Definidos

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Uma alcunha para ponteiro compartilhado para uma instância desta classe. |

## Observações



É recomendável usar a [XmlWriter](../xmlwriter/) classe em vez disso. 

Objetos desta classe devem ser alocados somente usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. 

## Ver também

* Classe [XmlWriter](../xmlwriter/)
* Espaço de nomes [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)