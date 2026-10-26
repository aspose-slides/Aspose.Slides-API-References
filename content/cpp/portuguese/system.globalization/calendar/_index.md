---
title: Calendar
second_title: Referência da API Aspose.Slides para C++
description: "Calendário que define como as datas são manipuladas, calculadas, formatadas, etc. As operações de definição são habilitadas apenas em objetos que não são somente leitura. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 1
url: /pt/system.globalization/calendar/
---
## Calendar classe

[Calendar](./) que define como as datas são manipuladas, calculadas, formatadas, etc. Operações de definição são habilitadas apenas em objetos não somente leitura. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class Calendar : public System::ICloneable
```

## Methods

| Método | Descrição |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | Adiciona dias ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | Adiciona horas ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Adiciona milissegundos ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | Adiciona minutos ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | Adiciona meses ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | Adiciona segundos ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | Adiciona semanas ao ponto de tempo. |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | Adiciona anos ao ponto de tempo. |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | Informação RTTI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Cria uma cópia do objeto atual e retorna um ponteiro compartilhado para ele. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | Obtém o tipo de algoritmo. |
| int [get_CurrentEra](./get_currentera/)() const | Obtém o índice da era atual. |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | Obtém o valor da era atual. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | Obtém a lista de eras existentes no calendário. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | Obtém o identificador do calendário. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Verifica se o calendário é somente leitura. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Ponto máximo no tempo suportado pelo calendário. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Ponto mínimo no tempo suportado pelo calendário. |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Obtém o último ano que pode ser representado por 2 dígitos. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | Obtém o dia do mês para o ponto de tempo especificado. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | Obtém o dia da semana para o ponto de tempo especificado. |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | Obtém o dia do ano para o ponto de tempo especificado. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Obtém o número de dias no mês específico. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Obtém o número de dias no mês específico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Obtém o número de dias no ano específico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Obtém o número de dias no ano específico. |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | Obtém a era para o ponto de tempo especificado. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite o hash de objetos personalizados. |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | Obtém as horas para o ponto de tempo especificado. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Obtém o mês bissexto para o ano especificado. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Obtém o mês bissexto para o ano especificado. |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | Obtém os milissegundos para o ponto de tempo especificado. |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | Obtém os minutos para o ponto de tempo especificado. |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | Obtém o mês para o ponto de tempo especificado. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Obtém o número de meses no ano especificado. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Obtém o número de meses no ano especificado. |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | Obtém os segundos para o ponto de tempo especificado. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Obtém a semana do ano para o ponto de tempo especificado. |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | Obtém o ano para o ponto de tempo especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Verifica se o dia é bissexto. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Verifica se o dia é bissexto. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Verifica se o mês é bissexto. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Verifica se o mês é bissexto. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Verifica se o ano é bissexto. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Verifica se o ano é bissexto. |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | Verifica valores de ano, mês, dia e era. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | Obtém a versão somente leitura do calendário. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Define o último ano que pode ser representado por 2 dígitos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Constrói o objeto [DateTime](../../system/datetime/) a partir de componentes. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Constrói o objeto [DateTime](../../system/datetime/) a partir de componentes. |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | Converte o ano para ano de 4 dígitos usando a propriedade TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)