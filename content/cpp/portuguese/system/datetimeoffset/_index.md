---
title: DateTimeOffset
second_title: Referência da API Aspose.Slides para C++
description: "Contém a data e a hora do dia relativa ao Tempo Universal Coordenado. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo às funções como argumento."
type: docs
weight: 235
url: /pt/system/datetimeoffset/
---
## DateTimeOffset classe

Contém a data e a hora do dia relativa ao Tempo Universal Coordenado. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../smartptr/) e use esse ponteiro para passá-lo às funções como argumento.

```cpp
class DateTimeOffset
```

## Métodos

| Método | Descrição |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Adiciona um intervalo de tempo especificado ao objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Adiciona um número especificado de dias ao objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Adiciona um número especificado de horas ao objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Adiciona um número especificado de milissegundos ao objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Adiciona um número especificado de minutos ao objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Adiciona um número especificado de meses ao objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Adiciona um número especificado de segundos ao objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Adiciona um número especificado de ticks ao objeto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Adiciona um número especificado de anos ao objeto [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Compara dois objetos [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Compara dois objetos [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Compara dois objetos [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Construtor padrão. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Construtor. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Construtor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Construtor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Construtor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Construtor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Construtor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Verifica se dois objetos [DateTimeOffset](./) representam o mesmo ponto no tempo. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Verifica se dois objetos [DateTimeOffset](./) representam o mesmo ponto no tempo. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Verifica se dois objetos [DateTimeOffset](./) representam o mesmo ponto no tempo. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Verifica se dois objetos [DateTimeOffset](./) representam o mesmo ponto no tempo e têm o mesmo deslocamento. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Verifica se dois objetos [DateTimeOffset](./) representam o mesmo ponto no tempo e têm o mesmo deslocamento. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) hora de arquivo para data e hora com deslocamento de horário local. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time para objeto [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time para objeto [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Obtém o componente de data do objeto atual. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Obtém o valor [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Obtém o dia do mês do objeto atual. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Obtém o dia da semana do objeto atual. |
| int [get_DayOfYear](./get_dayofyear/)() const | Obtém o dia do ano do objeto atual. |
| int [get_Hour](./get_hour/)() const | Obtém o componente de hora do objeto atual. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Obtém o valor [DateTime](../datetime/) que representa a data e hora local. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Obtém o componente de milissegundo do objeto atual. |
| int [get_Minute](./get_minute/)() const | Obtém o componente de minuto do objeto atual. |
| int [get_Month](./get_month/)() const | Obtém o componente de mês do objeto atual. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Obtém [DateTimeOffset](./) cuja data e hora são definidas como o horário local atual e cujo deslocamento é definido como o deslocamento do horário local. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Obtém o deslocamento em relação ao UTC. |
| constexpr int [get_Second](./get_second/)() const | Obtém o componente de segundo do objeto atual. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Obtém o número de ticks do objeto atual. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Obtém a hora do dia do objeto atual. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Obtém o valor [DateTime](../datetime/) que representa a data e hora UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Obtém [DateTimeOffset](./) cuja data e hora são definidas como o horário UTC atual e cujo deslocamento é [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Obtém o número de ticks do objeto atual em horário UTC. |
| int [get_Year](./get_year/)() const | Obtém o componente de ano do objeto atual. |
| int [GetHashCode](./gethashcode/)() const | Obtém o código hash para o objeto [DateTimeOffset](./) atual. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Determina se o objeto atual e o objeto [DateTimeOffset](./) especificado representam valores de data e hora distintos. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Retorna uma nova instância da classe [DateTimeOffset](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o intervalo de tempo especificado. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Retorna uma nova instância da classe [DateTimeOffset](./) que representa o valor de data e hora que resulta da subtração do intervalo de tempo especificado do valor representado pelo objeto atual. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Retorna uma instância da classe [TimeSpan](../timespan/) que representa o intervalo de tempo entre os valores de data e hora representados pelos objetos atual e especificado. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Determina se o objeto atual representa o valor de data e hora que é anterior ao valor representado pelo objeto [DateTimeOffset](./) especificado. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Determina se o objeto atual representa o valor de data e hora que é anterior ou igual ao valor representado pelo objeto [DateTimeOffset](./) especificado. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Determina se o objeto atual e o objeto [DateTimeOffset](./) especificado representam o mesmo valor de data e hora. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Determina se o objeto atual representa o valor de data e hora que é posterior ao valor representado pelo objeto [DateTimeOffset](./) especificado. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Determina se o objeto atual representa o valor de data e hora que é posterior ou igual ao valor representado pelo objeto [DateTimeOffset](./) especificado. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Converte a string especificada para o equivalente [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte a string especificada para o objeto [DateTimeOffset](./) usando o provedor de formato e o estilo de formatação especificados. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte a string especificada para o objeto [DateTimeOffset](./) usando o formato, o provedor de formato e o estilo de formatação especificados. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte a string especificada para o objeto [DateTimeOffset](./) usando os formatos, o provedor de formato e o estilo de formatação especificados. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Subtrai um intervalo de tempo especificado do objeto atual. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Subtrai um valor [DateTimeOffset](./) especificado do objeto atual. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Converte o objeto atual para o tempo de arquivo [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Converte o objeto atual para um objeto que representa o horário local. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Substitui o deslocamento do objeto atual pelo deslocamento especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte o objeto atual para string usando o formato e o provedor de formato especificados. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte o objeto atual para string usando o provedor de formato especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converte o objeto atual para string usando o formato especificado. |
| [String](../string/) [ToString](./tostring/)() const | Converte o objeto atual para string. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Converte o objeto atual para um objeto que representa o horário UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Obtém os milissegundos decorridos desde o início da época Unix. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Obtém os segundos decorridos desde o início da época Unix. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Tenta converter a string especificada para o objeto [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tenta converter a string especificada para o objeto [DateTimeOffset](./) usando o provedor de formato e o estilo de formatação especificados. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tenta converter a string especificada para o objeto [DateTimeOffset](./) usando os formatos, o provedor de formato e o estilo de formatação especificados. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tenta converter a string especificada para o objeto [DateTimeOffset](./) usando o formato, o provedor de formato e o estilo de formatação especificados. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retorna um objeto [TypeInfo](../typeinfo/) que representa a estrutura [TimeSpan](../timespan/). |

## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Obtém o deslocamento máximo em ticks. |
| static [MaxValue](./maxvalue/) | Obtém o maior valor [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Obtém o deslocamento mínimo em ticks. |
| static [MinValue](./minvalue/) | Obtém o valor [DateTimeOffset](./) mais antigo. |
| static [UnixEpoch](./unixepoch/) | Obtém o início da época Unix. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)