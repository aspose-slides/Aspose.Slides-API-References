---
title: String
second_title: Aspose.Slides para C++ API Reference
description: "Classe String usada em toda a biblioteca. É um substituto para C# System.String ao traduzir código. Por razões de otimização, não é considerado uma subclasse de Object. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 1275
url: /pt/system/string/
---
## classe String


[String](./) classe usada em toda a biblioteca. É um substituto para C# [System.String](./) ao traduzir código. Por razões de otimização, não é considerado uma subclasse de [Object](../object/). Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos deste tipo.

```cpp
class String
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) é um tipo valor no lado C++ que implicitamente (sem herança) implementa algumas interfaces. |
| const UChar * [begin](./begin/)() const | Retorna um ponteiro para o início do buffer de string real. Nunca realoca nada. Não garante que o buffer seja terminado por nulo. |
| [String](./) [Clone](./clone/)() const | Cria uma cópia da string atual. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Compara dois substrings usando operador menor-igual-maior. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Compara dois substrings usando operador menor-igual-maior. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Compara duas strings usando operador menor-igual-maior. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Compara duas strings usando operador menor-igual-maior. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Compara duas strings usando operador menor-igual-maior. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Compara duas strings usando operador menor-igual-maior. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Compara duas strings usando modo ordinal. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Compara duas strings usando modo ordinal. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Compara duas strings no estilo 'menor-igual-maior'. Usa a cultura atual. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Concatena strings. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Concatena strings. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatena strings. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatena strings. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Verifica se str é um substring da string atual. |
| **bool** [Contains](./contains/)(char16_t) const | Verifica se a string contém o caractere fornecido. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Cria uma cópia da string. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Copia caracteres da string para elementos de array existentes. Nenhum redimensionamento é realizado. |
| const UChar * [end](./end/)() const | Retorna um ponteiro para o final do buffer de string real. Nunca realoca nada. Não garante que o buffer seja terminado por nulo. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Verifica se a string termina com o substring especificado. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Verifica se a string termina com o substring especificado. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Verifica se a string termina com o substring especificado. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) comparação de igualdade. Vários modos fornecidos pela enumeração StringComparison são suportados. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) comparação de igualdade. Usa o modo de comparação [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Compara duas strings por igualdade usando modo de comparação Ordial. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Compara duas strings por igualdade. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Tenta converter um [String](./) para uma string ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formata a string no estilo C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formata a string no estilo C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formata a string no estilo C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formata a string no estilo C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formata a string no estilo C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Cria [String](./) a partir de string ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Cria [String](./) a partir de string ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Cria [String](./) a partir de string ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Cria [String](./) a partir de string utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Cria [String](./) a partir de string utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Cria [String](./) a partir de string utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Cria [String](./) a partir de string utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Cria [String](./) a partir de string utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Cria [String](./) a partir de string utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Cria [String](./) a partir de widestring. |
| int [get_Length](./get_length/)() const | Obtém o comprimento da string. |
| int [GetHashCode](./gethashcode/)() const | Calcula o hash da string contida. Implementado em ICU, não corresponde aos hashes em C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Busca avançada de substring. |
| int [IndexOf](./indexof/)(char_t, int) const | Busca avançada de caractere. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Busca avançada de caractere em substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Busca avançada de substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Busca avançada de substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Busca avançada de substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Busca avançada de substring. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Busca avançada de caractere. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Consequentemente procura todos os caracteres de str nesta. Se o primeiro caractere for encontrado, sua posição é retornada; caso contrário, procura o segundo e assim por diante. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Procura por quaisquer dos caracteres passados em toda a string. Compara o primeiro caractere da string com todos os caracteres em anyOf, depois o segundo e assim por diante. Retorna o índice do primeiro que corresponde a qualquer um dos caracteres-alvo. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Procura por quaisquer dos caracteres passados em uma substring. Compara o primeiro caractere da string com todos os caracteres em anyOf, depois o segundo e assim por diante. Retorna o índice do primeiro que corresponde a qualquer um dos caracteres-alvo. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Procura por quaisquer dos caracteres passados em uma substring. Compara o primeiro caractere da string com todos os caracteres em anyOf, depois o segundo e assim por diante. Retorna o índice do primeiro que corresponde a qualquer um dos caracteres-alvo. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Insere uma substring na posição especificada. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Verifica se o objeto string é do tipo especificado por [TypeInfo](../typeinfo/) passado. |
| **bool** [IsAsciiString](./isasciistring/)() const | Indica se um [String](./) contém apenas símbolos ASCII. |
| **bool** [IsEmpty](./isempty/)() const | Verifica se a string é não nula e vazia. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Verifica se a string Unicode está normalizada usando o formulário de normalização especificado. |
| **bool** [IsNull](./isnull/)() const | Verifica se a string é considerada nula. [String](./) é nula somente se for construída via construtor [String()](./string/), movida, copiada ou atribuída a partir de string nula ou se o método [reset()](./reset/) for chamado. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Verifica se a string está vazia ou é considerada nula. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Verifica se a string passada é nula ou vazia. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Indica se uma string especificada é nula, vazia ou consiste apenas de caracteres de espaço em branco. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Une um array usando a string como separador. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Une um array usando a string como separador. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Une um array usando a string como separador. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Une um array usando a string como separador. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Busca retroativa de substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Busca retroativa de substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Busca retroativa de substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Busca retroativa de substring. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Busca retroativa de caractere. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Busca retroativa de caractere. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Busca retroativa de caractere. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Procura por quaisquer dos caracteres passados em toda a string de trás para frente. Compara o último caractere da string com todos os caracteres em anyOf, depois o anterior e assim por diante. Retorna o índice da primeira correspondência encontrada. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Procura por quaisquer dos caracteres passados em uma substring de trás para frente. Compara o último caractere da string com todos os caracteres em anyOf, depois o anterior e assim por diante. Retorna o índice da primeira correspondência encontrada. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Procura por quaisquer dos caracteres passados em uma substring de trás para frente. Compara o último caractere da string com todos os caracteres em anyOf, depois o anterior e assim por diante. Retorna o índice da primeira correspondência encontrada. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normaliza a string Unicode usando o formulário de normalização especificado. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Converte a string para um span somente leitura. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Operador de comparação de desigualdade. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Verifica se a string não é nula. Aplica a mesma lógica da chamada [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) operador de concatenação. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) concatenação com literal de string ou ponteiro de string de caracteres. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Adiciona um caractere ao final da string. |
| [String](./) [operator+](./operator_plus/)(int) const | Adiciona a representação em string de um valor inteiro ao final da string. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Adiciona a representação em string de um valor inteiro sem sinal ao final da string. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Adiciona a representação em string de um valor de ponto flutuante ao final da string. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Adiciona a representação em string de um valor inteiro ao final da string. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Adiciona a representação em string de um objeto de tipo referência ao final da string. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Adiciona a representação em string de um objeto de tipo referência ao final da string. |
| [String](./) [operator+](./operator_plus/)(T) const | Adiciona a representação em string de um valor booleano ao final da string. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Operador de atribuição de concatenação. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Operador de atribuição de concatenação. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Compara a ordem de strings. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Operador de atribuição. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Operador de atribuição por movimento. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Operador de comparação de igualdade. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se a string é nula. Aplica a mesma lógica da chamada [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Compara a ordem de strings. |
| char_t [operator[]](./operator[]/)(int) const | Obtém o caractere na posição especificada. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Adiciona preenchimento à esquerda da string original. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Adiciona preenchimento à direita da string original. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Retorna o iterador reverso para o último caractere (se houver) do buffer de string real. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Extrai tudo, exceto a substring, da string atual. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Retorna o iterador reverso para antes do primeiro caractere (se houver) do buffer de string real. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Substitui todas as ocorrências do caractere na string. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Substitui todas as ocorrências da busca nesta string. |
| [String](./)\& [reset](./reset/)() | Define a string como nula. É análogo a 'string_variable_name = null' em C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Define o caractere na posição especificada. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por caractere. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por caractere. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por um de dois caracteres. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por um dos caracteres especificados. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por um dos caracteres especificados. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Divide a string por substring. Atualmente, suporta apenas um array de separadores com zero ou um elemento. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Verifica se a string começa com a substring especificada. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Verifica se a string começa com a substring especificada. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Verifica se a string começa com a substring especificada. |
|  [String](./string/)() | Construtor padrão. Cria um objeto string que é considerado nulo. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Constrói a string com base em literal de string. Considera o literal como uma string terminada em nulo, calcula o comprimento da string alvo com base no tamanho do literal. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Constrói a string com base em ponteiro para string de caracteres. Trata a string apontada como terminada em nulo, calcula o comprimento da string alvo com base no caractere nulo. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Constrói a string com base em literal de string. Considera o literal como uma string terminada em nulo em UTF8, calcula o comprimento da string alvo com base no tamanho do literal. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Constrói a string com base em ponteiro para string de caracteres. Trata a string apontada como terminada em nulo em UTF8, calcula o comprimento da string alvo com base no caractere nulo. |
|  [String](./string/)(const char16_t *, int) | Constrói a string a partir de ponteiro para string de caracteres e comprimento explícito. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Inicializa uma nova instância da classe [System.String](./) com os caracteres Unicode indicados no span somente leitura especificado. |
|  [String](./string/)(const char *, int) | Constrói a string a partir de ponteiro para string de caracteres e comprimento explícito. |
|  [String](./string/)(const char16_t *, int, int) | Constrói a string a partir de ponteiro para string de caracteres a partir da posição inicial usando o comprimento. |
| explicit  [String](./string/)(const char16_t, int) | Construtor de preenchimento. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Construtor nullptr. Declarado como template para resolver prioridades com outros construtores template. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Constrói a string com base em literal widestring. Considera o literal como uma string terminada em nulo, calcula o comprimento da string alvo com base no tamanho do literal. A conversão de **wchar_t** é demorada em algumas plataformas, portanto não são permitidas conversões implícitas. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Constrói a string com base em ponteiro para string widecharacter. Trata a string apontada como terminada em nulo, calcula o comprimento da string alvo com base no caractere nulo. A conversão de **wchar_t** é demorada em algumas plataformas, portanto não são permitidas conversões implícitas. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Constrói a string a partir de ponteiro para widecharacter e comprimento explícito. A conversão de **wchar_t** é demorada em algumas plataformas, portanto não são permitidas conversões implícitas. |
| explicit  [String](./string/)(const **wchar_t**, int) | Construtor de preenchimento. A conversão de **wchar_t** é demorada em algumas plataformas, portanto não são permitidas conversões implícitas. |
|  [String](./string/)(const [String](./)\&) | Construtor de cópia. |
|  [String](./string/)([String](./)\&&) | Construtor de movimento. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Converte o array inteiro de caracteres para string. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Converte subintervalo do array de caracteres para string. Se os parâmetros estiverem fora dos limites do array, uma string vazia será construída. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Envolve UnicodeString em [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Construtor de movimento. |
| explicit  [String](./string/)(const std::wstring\&) | Cria [String](./) a partir de widestring. |
| explicit  [String](./string/)(const std::u16string\&) | Cria [String](./) a partir de string utf16. |
| explicit  [String](./string/)(const std::string\&) | Cria [String](./) a partir de string std::string apresentada no formato UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Cria [String](./) a partir de string std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Extrai substring. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Extrai substring. |
| std::string [ToAsciiString](./toasciistring/)() const | Converte a string para std::string. Usa codificação ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Converte a string ou substring para array de bytes. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Converte a string ou substring para array de caracteres. |
| [String](./) [ToLower](./tolower/)() const | Converte todos os caracteres da string para minúsculas. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converte todos os caracteres da string para minúsculas usando cultura específica. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Converte todos os caracteres da string para minúsculas usando cultura invariável. |
| [String](./) [ToString](./tostring/)() const | Wrapper para manipular a classe [String](./) em contextos onde [ToString()](./tostring/) é chamado em objetos de tipo valor. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Wrapper para manipular a classe [String](./) em contextos onde [ToString()](./tostring/) é chamado em objetos de tipo valor. |
| std::u16string [ToU16Str](./tou16str/)() const | Converte a string para std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Converte a string para std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Converte todos os caracteres da string para maiúsculas. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converte todos os caracteres da string para maiúsculas usando cultura específica. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Converte todos os caracteres da string para maiúsculas usando cultura invariável. |
| std::string [ToUtf8String](./toutf8string/)() const | Converte a string para std::string. Usa codificação UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Converte a string para std::wstring. |
| [String](./) [Trim](./trim/)() const | Remove todos os caracteres de espaço em branco do início e do fim da string. |
| [String](./) [Trim](./trim/)(char_t) const | Remove todas as ocorrências do caractere passado do início e do fim da string. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Remove todas as ocorrências dos caracteres passados do início e do fim da string. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Remove todas as ocorrências dos caracteres passados do início e do fim da string. |
| [String](./) [TrimEnd](./trimend/)() const | Remove todos os caracteres de espaço em branco do fim da string. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Remove todas as ocorrências do caractere passado do fim da string. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Remove todas as ocorrências dos caracteres passados do fim da string. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Remove todas as ocorrências dos caracteres passados do fim da string. |
| [String](./) [TrimStart](./trimstart/)() const | Remove todos os caracteres de espaço em branco do início da string. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Remove todas as ocorrências do caractere passado do início da string. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Remove todas as ocorrências dos caracteres passados do início da string. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Remove todas as ocorrências dos caracteres passados do início da string. |
| const UChar * [u_str](./u_str/)() const | Retorna buffer terminada em nulo no estilo ICU. Pode realocar a string. |
|  [~String](./~string/)() | Destrutor. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Empty](./empty/) | String vazia. |
| static [Null](./null/) | String nula. |

## Tipos de Definição

| Typedef | Descrição |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador reverso. |

## Observações



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Construa uma string a partir do array de caracteres e imprima-a.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Construa uma string a partir do array de bytes e imprima-a.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Remova os espaços da string abaixo e imprima-a.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Imprima o número de palavras na .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Ver Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)