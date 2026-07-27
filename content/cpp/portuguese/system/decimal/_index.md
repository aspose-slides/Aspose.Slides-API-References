---
title: Decimal
second_title: Referência da API Aspose.Slides para C++
description: "Representa um número decimal. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 261
url: /pt/system/decimal/
---
## classe Decimal

Representa um número decimal. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos deste tipo.

```cpp
class Decimal
```

## Métodos

| Method | Descrição |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Adiciona dois valores [Decimal](./) especificados. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Retorna o menor valor integral que é maior ou igual ao valor especificado. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Determina se o valor representado pelo primeiro objeto [Decimal](./) é menor, igual ou maior que o valor representado pelo segundo objeto [Decimal](./). |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Determina se o valor representado pelo objeto atual é menor, igual ou maior que o valor representado pelo objeto especificado. |
| [Decimal](./decimal/)() | Constrói uma instância que representa 0. |
| [Decimal](./decimal/)(std::int8_t) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(std::int16_t) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(std::int32_t) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(std::int64_t) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(std::uint8_t) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(std::uint16_t) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(std::uint32_t) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(std::uint64_t) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(**float**) | Constrói uma instância que representa o valor especificado. |
| [Decimal](./decimal/)(**double**) | Constrói uma instância que representa o valor especificado. |
| explicit [Decimal](./decimal/)(const std::string\&) | Constrói uma instância que representa um valor cuja representação em string é especificada como uma instância da classe std::string. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Constrói um objeto [Decimal](./) a partir dos componentes especificados. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Constrói uma instância da classe [Decimal](./) que representa o mesmo número do objeto [Decimal](./) especificado. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Constrói uma instância da classe [Decimal](./) a partir de um array de inteiros contendo uma representação binária. |
| [Decimal](./decimal/)(std::nullptr_t) | Sempre lança ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Constrói uma instância da classe [Decimal](./) representando o valor especificado. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Divide dois valores [Decimal](./) especificados. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Determina se os valores representados pelo objeto atual e pelo objeto especificado são iguais. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina se os valores representados pelo objeto atual e pelo objeto especificado são iguais. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Determina se os valores representados pelos objetos especificados são iguais. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Retorna o maior valor integral que é menor ou igual ao valor especificado. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) o valor de moeda OLE especificado para o valor equivalente [Decimal](./). NÃO IMPLEMENTADO. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Converte o objeto [Decimal](./) especificado na representação binária do valor que ele representa. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) o valor [Decimal](./) especificado para um array de bytes. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Obtém o código de tipo do objeto. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Multiplica dois valores [Decimal](./) especificados. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Retorna uma nova instância da classe [Decimal](./) que representa um valor resultante da negação do valor representado pelo objeto especificado. |
| explicit [operator bool](./operator_bool/)() const | Converte o valor representado pelo objeto atual para um valor booleano. |
| explicit [operator double](./operator_double/)() const | Converte o valor representado pelo objeto atual para um valor de ponto flutuante de precisão dupla. |
| explicit [operator float](./operator_float/)() const | Converte o valor representado pelo objeto atual para um valor de ponto flutuante de precisão simples. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Determina se os valores representados pelo objeto atual e pelo objeto especificado não são iguais. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina se o valor representado pelo objeto atual é diferente de 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Retorna uma nova instância da classe [Decimal](./) que representa um valor resultante da operação módulo com os valores representados pelo objeto atual e pelo objeto especificado. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Atribui ao objeto atual um novo valor que é o resultado da operação módulo com os valores representados pelo objeto atual e pelo objeto especificado. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Retorna uma nova instância da classe [Decimal](./) que representa um valor resultante da multiplicação dos valores representados pelo objeto atual e pelos objetos especificados. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Atribui ao objeto atual um novo valor que é o resultado da multiplicação dos valores representados pelo objeto atual e pelo objeto especificado. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Retorna uma nova instância da classe [Decimal](./) que representa um valor que é a soma dos valores representados pelo objeto atual e pelos objetos especificados. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Incrementa o valor representado pelo objeto atual. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Atribui ao objeto atual um novo valor que é a soma dos valores representados pelo objeto atual e pelo objeto especificado. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Retorna uma nova instância da classe [Decimal](./) que representa um valor resultante da subtração do valor representado pelo objeto especificado do valor representado pelo objeto atual. |
| [Decimal](./) [operator-](./operator_minus/)() const | Retorna uma nova instância da classe [Decimal](./) que representa um valor resultante da negação do valor representado pelo objeto atual. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Decrementa o valor representado pelo objeto atual. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Atribui ao objeto atual um novo valor que é o resultado da subtração do valor representado pelo objeto especificado do valor representado pelo objeto atual. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Retorna uma nova instância da classe [Decimal](./) que representa um valor resultante da divisão do valor representado pelo objeto atual pelo valor representado pelo objeto especificado. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Atribui ao objeto atual um novo valor que é o resultado da divisão do valor representado pelo objeto atual pelo valor representado pelo objeto especificado. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Determina se o valor representado pelo objeto atual é menor que o valor representado pelo objeto especificado. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Determina se o valor representado pelo objeto atual é menor ou igual ao valor representado pelo objeto especificado. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Atribui ao objeto atual o valor representado pelo objeto especificado. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Determina se os valores representados pelo objeto atual e pelo objeto especificado são iguais. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina se o valor representado pelo objeto atual é 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Determina se o valor representado pelo objeto atual é maior que o valor representado pelo objeto especificado. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Determina se o valor representado pelo objeto atual é maior ou igual ao valor representado pelo objeto especificado. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Converte a representação em string de um número decimal em uma instância equivalente da classe [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Converte a representação em string de um número decimal em uma instância equivalente da classe [Decimal](./) usando o estilo especificado. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a representação em string de um número decimal em uma instância equivalente da classe [Decimal](./) usando o provedor de formato especificado. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte a representação em string de um número decimal em uma instância equivalente da classe [Decimal](./) usando o estilo e o provedor de formato especificados. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Computa o resto após dividir dois valores [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o número inteiro mais próximo. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois números inteiros vizinhos. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Arredonda o valor especificado para o valor mais próximo com o número especificado de dígitos fracionários. Um parâmetro especifica o comportamento da função se o valor especificado estiver igualmente próximo de dois valores mais próximos. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Subtrai um valor [Decimal](./) especificado de outro. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Converte o valor [Decimal](./) para um valor inteiro sem sinal de 8 bits. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Converte o valor [Decimal](./) para número de ponto flutuante de precisão dupla. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Converte o valor [Decimal](./) para um inteiro assinado de 16 bits. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Converte o valor [Decimal](./) para um inteiro assinado de 32 bits. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Converte o valor [Decimal](./) para um inteiro assinado de 64 bits. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) o valor [Decimal](./) especificado para o valor equivalente de moeda OLE. NÃO IMPLEMENTADO. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Converte o valor [Decimal](./) para um inteiro assinado de 8 bits. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Converte o valor [Decimal](./) para número de ponto flutuante de precisão simples. |
| std::string [ToStdString](./tostdstring/)() const | Retorna uma instância de std::string que contém a representação em string do valor representado pelo objeto. |
| [String](../string/) [ToString](./tostring/)() const | Retorna a representação em string do valor representado pelo objeto. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte o objeto atual para string usando informações de formato específicas da cultura. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte o objeto atual para sua representação em string usando o formato de string especificado e informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../iformatprovider/) especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Retorna a representação em string do valor representado pelo objeto. Para uso interno. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Converte o valor [Decimal](./) para um valor inteiro sem sinal de 16 bits. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Converte o valor [Decimal](./) para um valor inteiro sem sinal de 32 bits. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Converte o valor [Decimal](./) para um valor inteiro sem sinal de 64 bits. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Retorna o objeto [Decimal](./) que representa um valor cujo parte integral é igual à do valor representado pelo objeto [Decimal](./) especificado, com todos os dígitos fracionários descartados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Converte a string especificada contendo a representação em string de um número para o valor equivalente [Decimal](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Converte a string especificada contendo a representação em string de um número para o valor equivalente [Decimal](./) usando as informações de formatação e estilo de número fornecidos. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retorna uma referência ao objeto [TypeInfo](../typeinfo/) que representa as informações de tipo da classe [Decimal](./). |
| [~Decimal](./~decimal/)() | Destrutor. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [MaxValue](./maxvalue/) | Representa o maior número que pode ser representado pela classe [Decimal](./). |
| static [MinusOne](./minusone/) | Representa o número -1. |
| static [MinValue](./minvalue/) | Representa o menor número que pode ser representado pela classe [Decimal](./). |
| static [One](./one/) | Representa o número 1. |
| static [Zero](./zero/) | Representa o número 0. |

## Tipos definidos

| Definição de tipo | Descrição |
| --- | --- |
| [number_type](./number_type/) | Um alias para Detail::decimal_number_type. |

## Observações



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)