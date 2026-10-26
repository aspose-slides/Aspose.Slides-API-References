---
title: Convert
second_title: Referência da API Aspose.Slides para C++
description: "A estrutura que contém métodos que realizam a conversão de valores de um tipo para valores de outro tipo. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos deste tipo."
type: docs
weight: 1561
url: /pt/system/convert/
---
## Estrutura de Conversão

A estrutura que contém métodos que realizam a conversão de valores de um tipo para os valores de outro tipo. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos desse tipo.

```cpp
class Convert
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NÃO IMPLEMENTADO. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Decodifica dados codificados em base-64 representados como um intervalo no array de caracteres Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Decodifica dados codificados em base-64 representados como uma string. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Retorna um valor TypeCode que representa o tipo do valor encapsulado especificado. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NÃO IMPLEMENTADO. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NÃO IMPLEMENTADO Implementação falsa, verifica se o valor é nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Codifica em base-64 um intervalo de elementos no array de bytes especificado e armazena os dados codificados como um array de caracteres Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica em base-64 um intervalo de elementos no array de bytes especificado e armazena os dados codificados como um array de caracteres Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Codifica em base-64 elementos no array de bytes especificado e retorna os dados codificados como uma string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Codifica em base-64 um intervalo de elementos no array de bytes especificado e retorna os dados codificados como uma string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica em base-64 elementos no array de bytes especificado e retorna os dados codificados como uma string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Codifica em base-64 um intervalo de elementos no array de bytes especificado e retorna os dados codificados como uma string. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Retorna o valor booleano especificado. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Converte o inteiro com sinal de 8 bits especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Converte o inteiro com sinal de 16 bits especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Converte o inteiro com sinal de 32 bits especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Converte o inteiro com sinal de 64 bits especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Converte o número float especificado para um valor booleano equivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Converte o número double especificado para um valor booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um valor booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Conversão não suportada. Sempre lança InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Conversão não suportada. Sempre lança InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Converte a string nula especificada para o valor booleano equivalente. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Converte a string C especificada para o valor do tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Converte a string especificada para o valor do tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada para o valor do tipo bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor booleano equivalente. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Converte o valor booleano especificado para um inteiro sem sinal de 8 bits equivalente. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Retorna o inteiro sem sinal de 8 bits especificado. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Converte o inteiro com sinal de 8 bits especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Converte o inteiro com sinal de 16 bits especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Converte o inteiro com sinal de 32 bits especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Converte o inteiro com sinal de 64 bits especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Converte o número float especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Converte o número double especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Converte o caractere unicode especificado para um inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Conversão não suportada. Sempre lança InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Converte a string nula especificada para o valor inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Converte a string C contendo a representação textual de um número para o valor inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Converte a string contendo a representação textual de um número para o valor inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Converte a string contendo a representação textual de um número na base especificada para o valor inteiro sem sinal de 8 bits equivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string contendo a representação textual de um número para o valor inteiro sem sinal de 8 bits equivalente usando as informações de formatação fornecidas. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string contendo a representação textual de um número para o valor inteiro sem sinal de 8 bits equivalente usando as informações de formatação e estilo numérico fornecidos. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor inteiro sem sinal de 8 bits equivalente. |
| static char_t [ToChar](./tochar/)(**bool**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um caractere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Converte o inteiro com sinal de 8 bits especificado para um caractere unicode equivalente. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um caractere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Converte o inteiro com sinal de 16 bits especificado para um caractere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um caractere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Converte o inteiro com sinal de 32 bits especificado para um caractere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um caractere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Converte o inteiro com sinal de 64 bits especificado para um caractere unicode equivalente. |
| static char_t [ToChar](./tochar/)(**float**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Conversão não suportada. Sempre lança InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Retorna o caractere unicode especificado. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Conversão não suportada. Sempre lança InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Converte o primeiro e único caractere da string C especificada para um valor char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Converte o primeiro e único caractere da string especificada para um valor char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o primeiro e único caractere da string especificada para um valor char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um caractere unicode equivalente. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Conversão não suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Retorna a data e hora especificadas. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Converte a string especificada para uma instância da classe [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada para uma instância da classe [DateTime](../datetime/) usando as informações de formatação fornecidas. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor boxed especificado para o valor equivalente [DateTime](../datetime/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Converte o valor booleano especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Converte o inteiro com sinal de 8 bits especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Converte o inteiro com sinal de 16 bits especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Converte o inteiro com sinal de 32 bits especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Converte o inteiro com sinal de 64 bits especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Converte o número float especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Converte o número double especificado para um número decimal equivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Retorna o número decimal especificado. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Converte a string nula especificada para o valor equivalente [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Converte a c-string especificada que contém a representação textual de um número para o valor equivalente [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Converte a string especificada que contém a representação textual de um número para o valor equivalente [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor equivalente [Decimal](../decimal/) usando as informações de formatação fornecidas. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor equivalente [Decimal](../decimal/) usando os estilos de número especificados e as informações de formatação. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor boxed especificado para o valor equivalente [Decimal](../decimal/). |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Converte o valor booleano especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Converte o inteiro com sinal de 8 bits especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Converte o inteiro com sinal de 16 bits especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Converte o inteiro com sinal de 32 bits especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Converte o inteiro com sinal de 64 bits especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Converte o número float especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Retorna o número double especificado. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um número de ponto flutuante de dupla precisão equivalente. |
| static **double** [ToDouble](./todouble/)(char_t) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Converte a string nula especificada para o valor de ponto flutuante de dupla precisão equivalente. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Converte a c-string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação fornecidas. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor boxed especificado para um valor de ponto flutuante de dupla precisão. Se o tipo do valor boxed for [String](../string/), o formato de string especificado é usado durante a conversão. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Converte o valor booleano especificado para um inteiro com sinal de 16 bits equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um inteiro com sinal de 16 bits equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Converte o inteiro com sinal de 8 bits especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um inteiro com sinal de 16 bits equivalente. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Retorna o inteiro com sinal de 16 bits especificado. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Converte o inteiro com sinal de 32 bits especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Converte o inteiro com sinal de 64 bits especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Converte o número float especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Converte o número double especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Converte o caractere unicode especificado para um inteiro com sinal de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Converte a string nula especificada para o valor inteiro de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Converte a c-string especificada que contém a representação textual de um número para o valor inteiro de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Converte a string especificada que contém a representação textual de um número para o valor inteiro de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Converte a string especificada que contém a representação textual de um número na base especificada para o valor inteiro de 16 bits equivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor inteiro de 16 bits equivalente usando as informações de formatação fornecidas. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor inteiro de 16 bits equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor boxed especificado para o valor inteiro de 16 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Converte o valor booleano especificado para um inteiro com sinal de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um inteiro com sinal de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Converte o inteiro assinado de 8 bits especificado para um inteiro assinado de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um inteiro assinado de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Converte o inteiro assinado de 16 bits especificado para um inteiro assinado de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um inteiro assinado de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Retorna o inteiro assinado de 32 bits especificado. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um inteiro assinado de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(**int64_t**) | Converte o inteiro assinado de 64 bits especificado para um inteiro assinado de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(**float**) | Converte o número de ponto flutuante especificado para um inteiro assinado de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(**double**) | Converte o número double especificado para um inteiro assinado de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um inteiro assinado de 32 bits equivalente. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Converte o caractere Unicode especificado para um inteiro assinado de 32 bits equivalente. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Converte a string nula especificada para o valor inteiro de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const char_t *) | Converte a c-string especificada que contém a representação em texto de um número para o valor inteiro de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Converte a string especificada que contém a representação em texto de um número na base especificada para o valor inteiro de 32 bits equivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro de 32 bits equivalente usando as informações de formatação fornecidas. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro de 32 bits equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor inteiro de 32 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Converte o valor booleano especificado para um inteiro assinado de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um inteiro assinado de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Converte o inteiro assinado de 8 bits especificado para um inteiro assinado de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um inteiro assinado de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Converte o inteiro assinado de 16 bits especificado para um inteiro assinado de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um inteiro assinado de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Converte o inteiro assinado de 32 bits especificado para um inteiro assinado de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um inteiro assinado de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Retorna o inteiro assinado de 64 bits especificado. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Converte o número de ponto flutuante especificado para um inteiro assinado de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Converte o número double especificado para um inteiro assinado de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um inteiro assinado de 64 bits equivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Converte o caractere Unicode especificado para um inteiro assinado de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Converte a string nula especificada para o valor inteiro de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Converte a c-string especificada que contém a representação em texto de um número para o valor inteiro de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Converte a string especificada que contém a representação em texto de um número na base especificada para o valor inteiro de 64 bits equivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro de 64 bits equivalente usando as informações de formatação fornecidas. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro de 64 bits equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor inteiro de 64 bits equivalente. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Converte o valor booleano especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um inteiro assinado de 8 bits equivalente. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Retorna o inteiro assinado de 8 bits especificado. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Converte o inteiro assinado de 16 bits especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Converte o inteiro assinado de 32 bits especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Converte o inteiro assinado de 64 bits especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Converte o número de ponto flutuante especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Converte o número double especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Converte o caractere Unicode especificado para um inteiro assinado de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Converte a string nula especificada para o valor inteiro de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Converte a c-string especificada que contém a representação em texto de um número para o valor inteiro de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Converte a string especificada que contém a representação em texto de um número na base especificada para o valor inteiro de 8 bits equivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro sem sinal de 8 bits equivalente usando as informações de formatação fornecidas. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação em texto de um número para o valor inteiro de 8 bits equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor inteiro de 8 bits equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Converte o valor booleano especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Converte o inteiro assinado de 8 bits especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Converte o inteiro assinado de 16 bits especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Converte o inteiro assinado de 32 bits especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Converte o inteiro com sinal de 64 bits especificado para um número de ponto flutuante de precisão simples equivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Retorna o número float especificado. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Converte o número de precisão dupla especificado para um número de ponto flutuante de precisão simples equivalente. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um número de ponto flutuante de precisão simples equivalente. |
| static **float** [ToSingle](./tosingle/)(char_t) | Conversão não suportada. Sempre lança InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Conversão não suportada. Sempre lança InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Converte a string nula especificada para o valor de ponto flutuante de precisão simples equivalente. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Converte a c-string especificada que contém a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente usando as informações de formatação fornecidas. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de precisão simples equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor de ponto flutuante de precisão simples. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para string usando as informações de formatação específicas da cultura. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formatação específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formatação específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formatação específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formatação específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formatação específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formatação específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string usando o formato de string especificado e as informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Converte o valor especificado para string. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Converte o valor especificado para string usando o formato de string especificado. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Converte o array especificado de caracteres Unicode para string. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o array especificado de caracteres Unicode para string usando as informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Retorna o valor especificado; nenhuma conversão é realizada. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Converte o valor especificado para sua representação em string. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Converte o valor inteiro especificado para sua representação em string na base especificada. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Converte o valor inteiro especificado para sua representação em string na base especificada. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Converte o valor inteiro especificado para sua representação em string na base especificada. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Converte o valor inteiro especificado para sua representação em string na base especificada. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para sua representação em string. Se o tipo do valor encapsulado for [String](../string/), o formato de string especificado é usado durante a conversão. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Converte o valor booleano especificado para um inteiro sem sinal de 16 bits equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Converte o inteiro com sinal de 8 bits especificado para um inteiro sem sinal de 16 bits equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Retorna o inteiro sem sinal de 16 bits especificado. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Converte o inteiro com sinal de 16 bits especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Converte o inteiro com sinal de 32 bits especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Converte o inteiro com sinal de 64 bits especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Converte o número float especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Converte o número double especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um inteiro sem sinal de 16 bits equivalente. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Converte o caractere Unicode especificado para um inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Converte a string nula especificada para o valor inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Converte a c-string especificada que contém a representação em string de um número para o valor inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Converte a string especificada que contém a representação em string de um número para o valor inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Converte a string especificada que contém a representação em string de um número na base especificada para o valor inteiro sem sinal de 16 bits equivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação em string de um número para o valor inteiro sem sinal de 16 bits equivalente usando as informações de formatação fornecidas. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada que contém a representação em string de um número para o valor inteiro sem sinal de 16 bits equivalente usando as informações de formatação fornecidas e o estilo numérico. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor inteiro sem sinal de 16 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Converte o valor booleano especificado para um inteiro sem sinal de 32 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Converte o inteiro com sinal de 8 bits especificado para um inteiro sem sinal de 32 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Converte o inteiro com sinal de 16 bits especificado para um inteiro sem sinal de 32 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Retorna o inteiro sem sinal de 32 bits especificado. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Converte o inteiro assinado de 32 bits especificado para um inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Converte o inteiro sem sinal de 64 bits especificado para um inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Converte o inteiro assinado de 64 bits especificado para um inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Converte o número float especificado para um inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Converte o número double especificado para um inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um inteiro sem sinal de 32 bits equivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Converte o caractere unicode especificado para um inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Converte a null-string especificada para o valor inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Converte a c-string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Converte a string especificada contendo a representação textual de um número na base especificada para o valor inteiro sem sinal de 32 bits equivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 32 bits equivalente usando as informações de formatação fornecidas. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 32 bits equivalente usando as informações de formatação e o estilo numérico fornecidos. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor inteiro sem sinal de 32 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Converte o valor booleano especificado para um inteiro sem sinal de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Converte o inteiro sem sinal de 8 bits especificado para um inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Converte o inteiro assinado de 8 bits especificado para um inteiro sem sinal de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Converte o inteiro sem sinal de 16 bits especificado para um inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Converte o inteiro assinado de 16 bits especificado para um inteiro sem sinal de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Converte o inteiro sem sinal de 32 bits especificado para um inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Converte o inteiro assinado de 32 bits especificado para um inteiro sem sinal de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Retorna o inteiro sem sinal de 64 bits especificado. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Converte o inteiro assinado de 64 bits especificado para um inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Converte o número float especificado para um inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Converte o número double especificado para um inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Converte o número decimal especificado para um inteiro sem sinal de 64 bits equivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Converte o caractere unicode especificado para um inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Conversão não é suportada. Sempre lança InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Converte a null-string especificada para o valor inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Converte a c-string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Converte a string especificada contendo a representação textual de um número na base especificada para o valor inteiro sem sinal de 64 bits equivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 64 bits equivalente usando as informações de formatação fornecidas. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a string especificada contendo a representação textual de um número para o valor inteiro sem sinal de 64 bits equivalente usando as informações de formatação e o estilo numérico fornecidos. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte o valor encapsulado especificado para um valor inteiro sem sinal de 64 bits equivalente. |
## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)