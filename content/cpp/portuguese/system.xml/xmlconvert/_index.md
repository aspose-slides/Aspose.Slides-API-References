---
title: XmlConvert
second_title: Referência da API Aspose.Slides para C++
description: Codifica e decodifica nomes XML e fornece métodos para converter entre tipos em tempo de execução e tipos da linguagem de definição de esquema XML (XSD). Ao converter tipos de dados, os valores retornados são independentes de localidade.
type: docs
weight: 157
url: /pt/system.xml/xmlconvert/
---
## XmlConvert classe

Codifica e decodifica nomes XML, e fornece métodos para converter entre tipos em tempo de execução e tipos da linguagem de definição [Schema](../../system.xml.schema/) XML (XSD). Ao converter tipos de dados, os valores retornados são independentes de localidade.

```cpp
class XmlConvert : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Decodifica um nome. Este método faz o inverso dos métodos XmlConvert::EncodeName(String) e XmlConvert::EncodeLocalName(String). |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Converte o nome para um nome XML local válido. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Converte o nome para um nome XML válido. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Verifica se o nome é válido de acordo com a especificação XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associado ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Verifica se o caractere passado é um tipo de caractere não-dois-pontos válido. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Retorna a instância de caractere passada se o caractere no argumento for um caractere de ID público válido, caso contrário **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Verifica se o caractere passado é um tipo de caractere de Início de Nome válido. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Verifica se o caractere passado é um caractere de espaço em branco XML válido. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Verifica se o caractere passado é um caractere XML válido. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Verifica se o par substituto de caracteres passado é um caractere XML válido. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite copiar construtores de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite copiar construtores de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Converte o [String](../../system/string/) para um equivalente [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Converte o [String](../../system/string/) para um equivalente [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Converte o [String](../../system/string/) para um [DateTime](../../system/datetime/) usando o XmlDateTimeSerializationMode especificado. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) fornecido para um equivalente [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Converte o [String](../../system/string/) fornecido para um equivalente [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Converte o [String](../../system/string/) fornecido para um equivalente [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Converte o [String](../../system/string/) para um equivalente [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Converte o [String](../../system/string/) para um equivalente [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Converte o [Boolean](../../system/boolean/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Converte o [Char](../../system/char/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Converte o [Decimal](../../system/decimal/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Converte o [SByte](../../system/sbyte/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Converte o [Int16](../../system/int16/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Converte o [Int32](../../system/int32/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Converte o [Int64](../../system/int64/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Converte o [Byte](../../system/byte/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Converte o [UInt16](../../system/uint16/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Converte o [UInt32](../../system/uint32/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Converte o [UInt64](../../system/uint64/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Converte o [Single](../../system/single/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Converte o [Double](../../system/double/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Converte o [TimeSpan](../../system/timespan/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Converte o [DateTime](../../system/datetime/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Converte o [DateTime](../../system/datetime/) para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Converte o [DateTime](../../system/datetime/) para um [String](../../system/string/) usando o XmlDateTimeSerializationMode especificado. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Converte o [DateTimeOffset](../../system/datetimeoffset/) fornecido para um [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Converte o [DateTimeOffset](../../system/datetimeoffset/) fornecido para um [String](../../system/string/) no formato especificado. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Converte o [Guid](../../system/guid/) para um [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Converte o [String](../../system/string/) para um equivalente [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Verifica se o nome é um nome válido de acordo com a recomendação W3C Extended Markup Language. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Verifica se o nome é um **NCName** válido de acordo com a recomendação W3C Extended Markup Language. Um **NCName** é um nome que não pode conter dois-pontos. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Verifica se a string é um NMTOKEN válido de acordo com a recomendação W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Retorna a instância de string passada se todos os caracteres do argumento forem caracteres de ID público válidos. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Verifica se a string é um token válido de acordo com a recomendação W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Retorna a instância de string passada se todos os caracteres do argumento forem caracteres de espaço em branco válidos. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Retorna a string passada se todos os caracteres e pares substitutos da string forem caracteres XML válidos, caso contrário uma XmlException é lançada com informações sobre o primeiro caractere inválido encontrado. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Tipos definidos

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado de uma instância desta classe. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)