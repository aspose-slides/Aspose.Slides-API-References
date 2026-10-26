---
title: DateTime
second_title: Referência da API Aspose.Slides para C++
description: "Representa um valor específico de data e hora no continuum do tempo. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 222
url: /pt/system/datetime/
---
## DateTime classe

Representa um valor específico de data e hora no continuum temporal. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos deste tipo.

```cpp
class DateTime
```

## Métodos

| Método | Descrição |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Retorna uma nova instância da classe [DateTime](./) que representa um valor de data e hora resultante da adição do intervalo de tempo especificado ao valor de data e hora representado pelo objeto atual. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o número especificado de dias. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o número especificado de horas. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o número especificado de milissegundos. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o número especificado de minutos. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o número especificado de meses. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o número especificado de segundos. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o número especificado de intervalos de 100 nanossegundos. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora igual ao representado pelo objeto atual com o componente de ano incrementado pelo número especificado. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Compara dois valores representados pelas instâncias especificadas da classe [DateTime](./) e retorna o valor que indica as posições relativas dos valores na linha do tempo. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Compara dois valores de data e hora representados pelo objeto atual e pela instância especificada da classe [DateTime](./) e retorna o valor que indica as posições relativas dos valores na linha do tempo. |
| constexpr [DateTime](./datetime/)() | Constrói uma instância que representa o menor valor de data e hora possível, igual a MinValue. |
|  [DateTime](./datetime/)(int, int, int) | Constrói uma instância que representa um valor de data e hora especificado como um determinado ano, mês e dia. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Constrói uma instância que representa um valor de data e hora especificado como um determinado ano, mês e dia no calendário especificado. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Constrói uma instância que representa um valor de data e hora especificado como um determinado ano, mês, dia, hora, minuto e segundo. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Constrói uma instância que representa um valor de data e hora especificado como um determinado ano, mês, dia, hora, minuto e segundo. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Constrói uma instância que representa um valor de data e hora especificado como um determinado ano, mês, dia, hora, minuto e segundo no calendário especificado. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Constrói uma instância que representa um valor de data e hora especificado como um determinado ano, mês, dia, hora, minuto, segundo e milissegundo. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Constrói uma instância que representa um valor de data e hora especificado como um determinado ano, mês, dia, hora, minuto, segundo e milissegundo no calendário especificado. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Constrói uma instância que representa um valor de data e hora especificado como um número de ticks. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Constrói uma instância que representa um valor de data e hora especificado como um número de ticks. PARA USO INTERNO. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Constrói uma instância por cópia. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Retorna o número de dias no mês especificado do ano especificado. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Determina se as instâncias especificadas da classe [DateTime](./) representam o mesmo valor de data e hora. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Determina se a instância especificada da classe [DateTime](./) representa o mesmo valor de data e hora que o objeto atual. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Desserializa o valor de data e hora a partir do inteiro sem sinal de 64 bits especificado e define a nova instância da classe [DateTime](./) para esse valor. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Converte o File time especificado para uma instância da classe [DateTime](./) que representa o mesmo valor de data e hora como hora local. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Converte o File time especificado para uma instância da classe [DateTime](./) que representa o mesmo valor de data e hora como hora UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Retorna uma instância da classe [DateTime](./) que representa o valor de data e hora equivalente à OLE Automation Date especificada. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Converte o valor de tempo Unix especificado para uma instância da classe [DateTime](./). PARA USO INTERNO. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Retorna uma nova instância da classe [DateTime](./) que representa a parte de data da data e hora representada pelo objeto atual, com cada componente da parte de tempo definido como 0. |
| int [get_Day](./get_day/)() const | Retorna o número ordinal do dia no mês representado pelo objeto atual. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Retorna um valor que representa o dia da semana representado pelo objeto atual. |
| int [get_DayOfYear](./get_dayofyear/)() const | Retorna o número ordinal do dia no ano representado pelo objeto atual. |
| constexpr int [get_Hour](./get_hour/)() const | Retorna o componente de hora do valor de data e hora representado pelo objeto atual. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Retorna o valor que indica se a data e hora representada pelo objeto atual é local, UTC ou nenhum dos dois. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Retorna o componente de milissegundo do valor de data e hora representado pelo objeto atual. |
| constexpr int [get_Minute](./get_minute/)() const | Retorna o componente de minuto do valor de data e hora representado pelo objeto atual. |
| int [get_Month](./get_month/)() const | Retorna o número ordinal do mês no ano representado pelo objeto atual. |
| static [DateTime](./) [get_Now](./get_now/)() | Retorna uma instância da classe [DateTime](./) que representa o tempo atual como horário local. |
| constexpr int [get_Second](./get_second/)() const | Retorna o componente de segundo do valor de data e hora representado pelo objeto atual. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Retorna um número de intervalos de 100 nanossegundos decorridos desde 0:00:00 UTC, 1 de janeiro de 0001, no calendário gregoriano até a data e hora representada pelo objeto atual. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Retorna o valor que representa o intervalo de tempo do início do dia representado pelo objeto atual até o valor de data e hora representado pelo objeto atual. |
| static [DateTime](./) [get_Today](./get_today/)() | Retorna uma instância da classe [DateTime](./) que representa a data atual, com cada componente da parte de tempo definido como 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Retorna uma instância da classe [DateTime](./) que representa o tempo atual como UTC. |
| int [get_Year](./get_year/)() const | Retorna o ano representado pelo objeto atual. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Obtém as partes da data. PARA USO INTERNO. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com um dos especificadores padrão de formato de data e hora. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com o especificador padrão de formato de data e hora especificado. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com um dos especificadores padrão de formato de data e hora e o provedor de formato especificado. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retorna um array de strings onde cada elemento é a representação em string do objeto atual formatado com o especificador padrão de formato de data e hora especificado e o provedor de formato. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Determina se o valor de data e hora representado pelo objeto atual está dentro do intervalo de horário de verão para o fuso horário atual. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Determina se o ano especificado é um ano bissexto. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Determina se o objeto atual e o objeto [DateTime](./) especificado representam valores de data e hora distintos. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é a soma do valor representado pelo objeto atual e o intervalo de tempo especificado. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Define o objeto atual para o valor de data e hora que é a soma do valor representado pelo objeto atual e o intervalo de tempo especificado. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor representado pelo objeto atual. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Retorna uma instância da classe [TimeSpan](../timespan/) que representa o intervalo de tempo entre os valores de data e hora representados pelos objetos atual e especificado. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Define o objeto atual para o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor de data e hora representado pelo objeto atual. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Determina se o objeto atual representa o valor de data e hora que é anterior ao valor representado pelo objeto [DateTime](./) especificado. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Determina se o objeto atual representa o valor de data e hora que é anterior ou igual ao valor representado pelo objeto [DateTime](./) especificado. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Atribui o valor representado pela instância [DateTime](./) especificada ao objeto atual. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Determina se o objeto atual e o objeto [DateTime](./) especificado representam o mesmo valor de data e hora. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Determina se o objeto atual representa o valor de data e hora que é posterior ao valor representado pelo objeto [DateTime](./) especificado. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Determina se o objeto atual representa o valor de data e hora que é posterior ou igual ao valor representado pelo objeto [DateTime](./) especificado. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](./) equivalente. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](./) equivalente usando informações de formato específicas da cultura. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](./) equivalente usando o formato especificado e informações de formato específicas da cultura. O formato da representação de string deve corresponder exatamente ao formato especificado. Lança uma exceção se a conversão falhar. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](./) equivalente usando os formatos especificados, informações de formato específicas da cultura e estilo. O formato da representação de string deve corresponder exatamente a um ou mais dos formatos especificados. Lança uma exceção se a conversão falhar. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Constrói um novo objeto [DateTime](./) que representa o mesmo número de ticks que o objeto [DateTime](./) especificado e representa hora local, hora UTC ou nenhuma delas, conforme especificado pelo argumento **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor representado pelo objeto atual. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Retorna uma instância da classe [TimeSpan](../timespan/) que representa o intervalo de tempo entre os valores de data e hora representados pelos objetos atual e especificado. |
| **int64_t** [ToBinary](./tobinary/)() const | Serializa o objeto atual. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Retorna um valor que representa o valor de data e hora representado pelo objeto atual como File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Converte o valor de data e hora representado pelo objeto atual para File time UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora representado pelo objeto atual como hora local. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Retorna uma string que contém a representação de string de data longa do objeto atual. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Retorna uma string que contém a representação de string de hora longa do objeto atual. |
| **double** [ToOADate](./tooadate/)() const | Retorna o valor de data e hora representado pelo objeto atual como OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Retorna uma string que contém a representação de string de data curta do objeto atual. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Retorna uma string que contém a representação de string de hora curta do objeto atual. |
| [String](../string/) [ToString](./tostring/)() const | Retorna a representação de string do valor de data e hora representado pelo objeto atual usando as convenções de formatação definidas pela cultura atual. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Retorna uma representação de string do valor de data e hora representado pelo objeto atual usando o formato especificado e as convenções de formatação definidas pela cultura atual. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retorna uma representação de string do valor de data e hora representado pelo objeto atual usando as informações de formato especificadas. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retorna uma representação de string do valor de data e hora representado pelo objeto atual usando as informações de formato especificadas. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Retorna uma nova instância da classe [DateTime](./) que representa o valor de data e hora representado pelo objeto atual como UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Retorna um valor que representa o valor de data e hora representado pelo objeto atual como Unix time. FOR INTERNAL USE. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](./) equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](./) equivalente usando as informações de formato específicas da cultura e o estilo especificados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](./) equivalente usando o formato especificado, informações de formato específicas da cultura e estilo. O formato da representação de string deve corresponder exatamente ao formato especificado. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converte a representação de string especificada de um valor de data e hora para o objeto [DateTime](./) equivalente usando os formatos especificados, informações de formato específicas da cultura e estilo. O formato da representação de string deve corresponder exatamente a um ou mais dos formatos especificados. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retorna um objeto [TypeInfo](../typeinfo/) que contém informações sobre esta classe. |

## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | O número de intervalos de 100 nanossegundos no intervalo de tempo entre o valor [DateTime](./) mínimo possível e o máximo possível. |
| static [MaxValue](./maxvalue/) | Uma instância da classe [DateTime](./) que representa o valor máximo possível de data e hora. |
| static constexpr [MinTicks](./minticks/) | O número mínimo de ticks que uma instância da classe [DateTime](./) pode representar. |
| static [MinValue](./minvalue/) | Uma instância da classe [DateTime](./) que representa o valor mínimo possível de data e hora. |
| static constexpr [TicksPerDay](./ticksperday/) | O número de ticks em um dia. |
| static constexpr [TicksPerHour](./ticksperhour/) | O número de ticks em uma hora. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | O número de ticks em um microssegundo. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | O número de ticks em um milissegundo. |
| static constexpr [TicksPerMinute](./ticksperminute/) | O número de ticks em um minuto. |
| static constexpr [TicksPerSecond](./tickspersecond/) | O número de ticks em um segundo. |
| static [UnixEpoch](./unixepoch/) | Uma instância da classe [DateTime](./) que representa o início da época Unix (1970.01.01 00:00:00). |

## Observações

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Crie a instância da classe 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Imprima a instância em vários formatos.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)