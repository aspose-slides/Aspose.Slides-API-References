---
title: JapaneseCalendar
second_title: Referencia de la API de Aspose.Slides para C++
description: "Calendario japonés. Los objetos de esta clase sólo deben ser asignados usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 183
url: /es/system.globalization/japanesecalendar/
---
## Clase JapaneseCalendar

Japanese calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JapaneseCalendar : public System::Globalization::Calendar
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Agrega días al punto de tiempo. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Agrega horas al punto de tiempo. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Agrega milisegundos al punto de tiempo. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Agrega minutos al punto de tiempo. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Agrega meses al punto de tiempo. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Agrega segundos al punto de tiempo. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Agrega semanas al punto de tiempo. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Agrega años al punto de tiempo. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Información RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Crea una copia del objeto actual y devuelve un puntero compartido a él. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Obtiene el tipo de algoritmo. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Obtiene el índice de la era actual. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Obtiene el valor de la era actual. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Obtiene la lista de eras existentes en el calendario. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Comprueba si el calendario es de solo lectura. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Punto máximo en el tiempo que admite el calendario. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Punto mínimo en el tiempo que admite el calendario. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Obtiene el último año que puede representarse con dos dígitos. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Obtiene el día del mes para el punto de tiempo especificado. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Obtiene el día de la semana para el punto de tiempo especificado. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Obtiene el día del año para el punto de tiempo especificado. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Obtiene el número de días en un mes específico. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Obtiene el número de días en un mes específico. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Obtiene el número de días en un mes específico. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Obtiene el número de días en un año específico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Obtiene el número de días en un año específico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Obtiene el número de días en un año específico. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Obtiene la era para el punto de tiempo especificado. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Obtiene las horas para el punto de tiempo especificado. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Obtiene el mes bisiesto para el año especificado. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Obtiene el mes bisiesto para el año especificado. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Obtiene el mes bisiesto para el año especificado. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Obtiene los milisegundos para el punto de tiempo especificado. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Obtiene los minutos para el punto de tiempo especificado. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Obtiene el mes para el punto de tiempo especificado. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Obtiene el número de meses en el año especificado. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Información RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Información RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Obtiene los segundos para el punto de tiempo especificado. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Obtiene la semana del año para el punto de tiempo especificado. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Obtiene el año para el punto de tiempo especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Comprueba si el día es bisesto. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Comprueba si el día es bisesto. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Comprueba si el día es bisesto. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Comprueba si el mes es bisesto. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Comprueba si el mes es bisesto. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Comprueba si el mes es bisesto. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Comprueba si el año es bisesto. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Comprueba si el año es bisesto. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Comprueba si el año es bisesto. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Comprueba los valores de año, mes, día y era. |
|  [JapaneseCalendar](./japanesecalendar/)() | Constructor. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Obtiene la versión de solo lectura del calendario. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Establece el último año que puede representarse con dos dígitos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Construye un objeto [DateTime](../../system/datetime/) a partir de los componentes. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Construye un objeto [DateTime](../../system/datetime/) a partir de los componentes. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Construye un objeto [DateTime](../../system/datetime/) a partir de los componentes. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Convierte el año a un año de 4 dígitos usando la propiedad TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Véase también

* Clase [Calendar](../calendar/)
* Espacio de nombres [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)