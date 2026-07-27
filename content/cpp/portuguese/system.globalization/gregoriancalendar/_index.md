---
title: GregorianCalendar
second_title: Referência da API Aspose.Slides para C++
description: "Calendário gregoriano. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject() function. Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 131
url: /pt/system.globalization/gregoriancalendar/
---
## GregorianCalendar classe

Gregorian calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GregorianCalendar : public System::Globalization::Calendar
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Adiciona dias ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Adiciona horas ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Adiciona milissegundos ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Adiciona minutos ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Adiciona meses ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Adiciona segundos ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Adiciona semanas ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Adiciona anos ao ponto de tempo. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informação RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Cria uma cópia do objeto atual e retorna um ponteiro compartilhado para ele. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência ao estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor ao estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Obtém o tipo do algoritmo. |
| virtual [GregorianCalendarTypes](../gregoriancalendartypes/) [get_CalendarType](./get_calendartype/)() const | Obtém o tipo de calendário gregoriano. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Obtém o índice da era atual. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Obtém o valor da era atual. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Obtém a lista de eras existentes no calendário. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Verifica se o calendário é somente leitura. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Ponto máximo no tempo suportado pelo calendário. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Ponto mínimo no tempo suportado pelo calendário. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Obtém o último ano que pode ser representado por dois dígitos. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Obtém o dia do mês para o ponto de tempo especificado. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Obtém o dia da semana para o ponto de tempo especificado. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Obtém o dia do ano para o ponto de tempo especificado. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Obtém o número de dias no mês específico. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Obtém o número de dias no mês específico. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Obtém o número de dias no mês específico. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Obtém o número de dias no ano específico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Obtém o número de dias no ano específico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Obtém o número de dias no ano específico. |
| static [CalendarPtr](../calendarptr/) [GetDefaultInstance](./getdefaultinstance/)() | Obtém a instância padrão do calendário gregoriano. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Obtém a era para o ponto de tempo especificado. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite o hash de objetos personalizados. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Obtém as horas para o ponto de tempo especificado. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Obtém o mês bissexto para o ano especificado. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Obtém o mês bissexto para o ano especificado. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Obtém o mês bissexto para o ano especificado. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Obtém os milissegundos para o ponto de tempo especificado. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Obtém os minutos para o ponto de tempo especificado. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Obtém o mês para o ponto de tempo especificado. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Obtém o número de meses no ano especificado. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Informação RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Informação RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Obtém os segundos para o ponto de tempo especificado. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Obtém a semana do ano para o ponto de tempo especificado. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Obtém o ano para o ponto de tempo especificado. |
|  [GregorianCalendar](./gregoriancalendar/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Constrói um calendário gregoriano específico. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Verifica se o dia é bissexto. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Verifica se o dia é bissexto. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Verifica se o dia é bissexto. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Verifica se o mês é bissexto. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Verifica se o mês é bissexto. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Verifica se o mês é bissexto. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Verifica se o ano é bissexto. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Verifica se o ano é bissexto. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Verifica se o ano é bissexto. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Verifica os valores de ano, mês, dia e era. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Obtém a versão somente leitura do calendário. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| virtual void [set_CalendarType](./set_calendartype/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Define o tipo de calendário gregoriano. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Define o último ano que pode ser representado por dois dígitos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Constrói o objeto [DateTime](../../system/datetime/) a partir dos componentes. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Constrói o objeto [DateTime](../../system/datetime/) a partir dos componentes. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Constrói o objeto [DateTime](../../system/datetime/) a partir dos componentes. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Converte o ano para um ano de 4 dígitos usando a propriedade TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |

## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [ADEra](./adera/) | Era atual. |

## Veja Também

* Classe [Calendar](../calendar/)
* Espaço de nomes [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)