---
title: MathMatrix
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica el objeto Matrix, compuesto por elementos hijo dispuestos en una o más filas y columnas. Es importante notar que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes debe usar el objeto delimitador (IMathDelimiter). Los argumentos nulos pueden usarse para crear espacios vacíos en las matrices.
type: docs
weight: 950
url: /es/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix clase

Especifica el objeto Matrix, compuesto por elementos hijo dispuestos en una o más filas y columnas. Es importante notar que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes debe usar el objeto delimitador ([IMathDelimiter](../imathdelimiter/)). Se pueden usar argumentos nulos para crear espacios vacíos en las matrices.

```cpp
class MathMatrix : public Aspose::Slides::MathText::MathElementBase,
                   public Aspose::Slides::MathText::IMathMatrix,
                   public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## Métodos

| Método | Descripción |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Toma la función especificada usando esta instancia como argumento |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | Toma la función especificada usando esta instancia como argumento |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | Toma la función especificada usando esta instancia como argumento |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| void [DeleteColumn](./deletecolumn/)(**int32_t**) override | Elimina la columna especificada |
| void [DeleteRow](./deleterow/)(**int32_t**) override | Elimina la fila especificada |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Crea una fracción con este numerador y el denominador especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | Crea una fracción con este numerador y el denominador especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | Encierra un elemento matemático entre paréntesis |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | Encierra un elemento matemático en los caracteres especificados, como paréntesis u otros caracteres como marco |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Toma una función de un argumento usando esta instancia como nombre de la función |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | Toma una función de un argumento usando esta instancia como nombre de la función |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | Especifica la justificación vertical respecto al texto circundante. Los valores posibles son superior, inferior y centrado. Predeterminado: Centro |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Número de columnas en la matriz |
| **uint32_t** [get_ColumnGap](./get_columngap/)() override | El valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto). Si ColumnGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como número de incrementos de 0,5 em. En otros casos se ignora. Predeterminado: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() override | El tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0) |
| **bool** [get_HidePlaceholders](./get_hideplaceholders/)() override | Oculta los marcadores de posición para elementos de matriz vacíos. Predeterminado: false |
| **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() override | Anchura mínima de columna en twips (1/20 de punto). El espaciado de la brecha (también llamado \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) se suma a MinColumnWidth para determinar el espaciado total de la matriz [Column](../../aspose.slides/column/) (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0. |
| **int32_t** [get_RowCount](./get_rowcount/)() override | Número de filas en la matriz |
| **uint32_t** [get_RowGap](./get_rowgap/)() override | El valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto). Si RowGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como medio línea. Predeterminado: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() override | El tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | Obtiene los elementos hijos |
| [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) override | Obtiene la alineación horizontal de la columna especificada |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | Coloca este elemento en un grupo usando una llave rizada inferior |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | Coloca este elemento en un grupo usando un carácter de agrupación como una llave rizada inferior u otro |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | Elemento de la matriz |
| void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Elemento de la matriz |
| void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) override | Inserta una nueva columna después de la especificada. Inicialmente todos los elementos en la nueva columna son nulos. |
| void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) override | Inserta una nueva columna antes de la especificada. Inicialmente todos los elementos en la nueva columna son nulos. |
| void [InsertRowAfter](./insertrowafter/)(**int32_t**) override | Inserta una nueva fila después de la especificada. Inicialmente todos los elementos en la nueva fila son nulos. |
| void [InsertRowBefore](./insertrowbefore/)(**int32_t**) override | Inserta una nueva fila antes de la especificada. Inicialmente todos los elementos en la nueva fila son nulos. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | Toma la integral |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Toma la integral |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | Toma la integral sin límites |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | Toma la integral |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Toma la integral |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Une un elemento matemático y forma un bloque matemático |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | Une un texto matemático y forma un bloque matemático |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
|   [MathMatrix](./mathmatrix/)(**int32_t**, **int32_t**) | Inicializa una nueva instancia de la clase [MathMatrix](./). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Crea un operador N-ario |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Crea un operador N-ario |
|   [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | Establece una barra en la parte superior de este elemento |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | Especifica la justificación vertical respecto al texto circundante. Los valores posibles son superior, inferior y centrado. Predeterminado: Centro |
| void [set_ColumnGap](./set_columngap/)(**uint32_t**) override | El valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto). Si ColumnGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como número de incrementos de 0,5 em. En otros casos se ignora. Predeterminado: 0 |
| void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) override | El tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0) |
| void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) override | Oculta los marcadores de posición para elementos de matriz vacíos. Predeterminado: false |
| void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) override | Anchura mínima de columna en twips (1/20 de punto). El espaciado de la brecha (también llamado \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) se suma a MinColumnWidth para determinar el espaciado total de la matriz [Column](../../aspose.slides/column/) (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0. |
| void [set_RowGap](./set_rowgap/)(**uint32_t**) override | El valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto). Si RowGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como medio línea. Predeterminado: 0 |
| void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) override | El tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0) |
| void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | Establece la alineación horizontal de la columna especificada |
| void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | Establece la alineación horizontal de las columnas especificadas |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Toma el límite inferior |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | Toma el límite inferior |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Crea subíndice |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | Crea subíndice |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Crea subíndice y superíndice a la izquierda |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Crea subíndice y superíndice a la izquierda |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Crea subíndice y superíndice a la derecha |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Crea subíndice y superíndice a la derecha |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Crea superíndice |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | Crea superíndice |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Toma el límite superior |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | Toma el límite superior |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrece y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | Coloca este elemento en una caja con borde |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | Coloca este elemento en una caja con borde |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | Coloca este elemento en una caja no visual (agrupación lógica) que se usa para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como emulador de operador con o sin punto de alineación, servir como punto de salto de línea, o agruparse de forma que no se permitan saltos de línea dentro. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | Coloca en una matriz vertical |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | Establece una barra en la parte inferior de este elemento |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrece el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Comentarios

Ejemplo: 
```cpp
System::SharedPtr<IMathMatrix> matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Ver también

* Clase [MathElementBase](../mathelementbase/)
* Clase [IMathMatrix](../imathmatrix/)
* Clase [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* Espacio de nombres [Aspose::Slides::MathText](../)
* Biblioteca [Aspose.Slides](../../)