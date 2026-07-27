---
title: Encoding
second_title: Referência da API Aspose.Slides para C++
description: Serviços de codificação.
type: docs
weight: 222
url: /pt/system.text/encoding/
---
## Classe Encoding

[Encoding](./) serviços.

```cpp
class Encoding : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Clona o objeto de codificação. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Converte bytes entre duas codificações. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Converte bytes entre duas codificações. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compara codificações. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo de referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Obtém a codificação ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Obtém o objeto de codificação Unicode big-endian padrão. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Obtém o objeto de codificação UTF-32 big-endian padrão. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Obtém o nome de codificação compatível com o corpo do agente de e-mail. |
| virtual int [get_CodePage](./get_codepage/)() | Obtém o ID da página de códigos [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Obtém o fallback do decodificador. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Obtém a codificação padrão. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Obtém o fallback do codificador. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Obtém o nome de codificação legível por humanos. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Obtém o nome de codificação compatível com o cabeçalho do agente de e-mail. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Verifica se a codificação pode ser usada no navegador para exibir conteúdo. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Verifica se a codificação pode ser usada no navegador para salvar conteúdo. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Verifica se a codificação pode ser usada no cliente de e-mail para exibir conteúdo. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Verifica se a codificação pode ser usada no cliente de e-mail para salvar conteúdo. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Verifica se a codificação é somente leitura. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Verifica se a codificação é de byte único. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Obtém a codificação Latin1. PARA USO INTERNO. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Obtém o objeto de codificação Unicode padrão. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Obtém o objeto de codificação UTF-7 padrão. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Obtém o objeto de codificação UTF-8 padrão. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Somente interno, para ser usado pelas bibliotecas de classes: Não marcado e não valida a entrada. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Obtém o nome de codificação compatível com IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Obtém o ID da página de códigos [Windows](../../system.windows/). |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Obtém o número de caracteres necessários para codificar um buffer de caracteres. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Obtém o número de caracteres necessários para codificar um buffer de caracteres. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtém o número de caracteres necessários para codificar um buffer de caracteres. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Obtém o número de caracteres necessários para codificar uma string. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Obtém o número de caracteres necessários para codificar um buffer de caracteres. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Obtém o número de caracteres necessários para codificar um buffer de caracteres. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Obtém os bytes resultantes da codificação de um buffer de caracteres. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtém o número de caracteres necessários para decodificar um buffer de bytes. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtém o número de caracteres necessários para decodificar um buffer de bytes. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Obtém o número de caracteres necessários para decodificar um buffer de bytes. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Obtém os caracteres resultantes da decodificação de um buffer de bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtém os caracteres resultantes da decodificação de um buffer de bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtém os caracteres resultantes da decodificação de um buffer de bytes. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Obtém os caracteres resultantes da decodificação de um buffer de bytes. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Obtém um decodificador que encaminha solicitações para este objeto. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Obtém um codificador que encaminha solicitações para este objeto. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Obtém a codificação por nome. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Obtém a codificação por página de códigos. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Obtém a codificação por página de códigos. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Obtém a codificação por nome. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Obtém a lista de codificações conhecidas. |
| int [GetHashCode](./gethashcode/)() const override | Gera hash da codificação. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Obtém o número máximo de bytes necessários para codificar um número especificado de caracteres. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Obtém o número máximo de caracteres necessários para decodificar um número especificado de bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Retorna uma sequência de bytes que indica a codificação (por exemplo, BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Decodifica um buffer de bytes em uma string. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Decodifica um buffer de bytes em uma string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodifica um buffer de bytes em uma string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodifica um buffer de bytes em uma string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodifica um buffer de bytes em uma string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodifica um buffer de bytes em uma string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodifica um buffer de bytes em uma string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodifica um buffer de bytes em uma string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência o objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Define o fallback do decodificador. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Define o fallback do codificador. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Valor padrão da página de códigos. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [System::Text](../)
* Biblioteca [Aspose.Slides](../../)