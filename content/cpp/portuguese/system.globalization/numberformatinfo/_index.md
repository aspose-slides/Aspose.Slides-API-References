---
title: NumberFormatInfo
second_title: Referência da API Aspose.Slides para C++
description: "Mantém informações sobre como formatar números. Operações de definição (setter) estão habilitadas apenas em objetos que não são somente leitura. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject() . Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 248
url: /pt/system.globalization/numberformatinfo/
---
## classe NumberFormatInfo

Mantém informações sobre como formatar números. Operações de definição (setter) estão disponíveis apenas em objetos que não são somente leitura. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Métodos

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clona as informações de formato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Obtém o número de dígitos decimais da moeda. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Obtém o separador decimal da moeda. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Obtém o separador de agrupamento da moeda. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Obtém o número de dígitos decimais da moeda por grupo. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Obtém o padrão negativo da moeda. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Obtém o padrão positivo da moeda. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Obtém o símbolo da moeda. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Obtém as informações de formato numérico definidas pela cultura do thread atual. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Obtém um valor que especifica como exibir a forma de um dígito. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Obtém as informações de formato numérico definidas pela cultura invariante. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Verifica se o formato é somente leitura. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Obtém o símbolo Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Obtém os símbolos dos dígitos (0 a 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Obtém o símbolo de infinito negativo. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Obtém o sinal negativo. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Obtém o número de dígitos decimais. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Obtém o separador decimal. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Obtém o separador de agrupamento numérico. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Obtém o número de dígitos por grupo. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Obtém o padrão negativo de número. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Obtém o número de casas decimais em valores percentuais. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Obtém o separador decimal em valores percentuais. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Obtém o separador de agrupamento em valores percentuais. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Obtém o número de dígitos por grupo de valor percentual. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Obtém o padrão negativo de percentagem. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Obtém o padrão positivo de percentagem. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Obtém o símbolo de percentagem. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Obtém o símbolo de permil. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Obtém o símbolo de infinito positivo. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Obtém o sinal positivo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Obtém o formatador de tipo específico. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Obtém o formatador associado ao provedor de formato. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [NumberFormatInfo](./numberformatinfo/)() | Construtor padrão (invariante [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Obtém a versão somente leitura do formatador. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Define o número de dígitos decimais da moeda. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Define o separador decimal da moeda. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Define o separador de agrupamento da moeda. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Define o número de dígitos decimais da moeda por grupo. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Define o padrão negativo da moeda. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Define o padrão positivo da moeda. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Define o símbolo da moeda. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Define um valor que especifica como exibir a forma de um dígito. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Define o símbolo Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Define os símbolos dos dígitos (0 a 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Define o símbolo de infinito negativo. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Define o sinal negativo. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Define o número de dígitos decimais. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Define o separador decimal. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Define o separador de agrupamento numérico. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Define o número de dígitos por grupo. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Define o padrão negativo de número. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Define o número de casas decimais em valores percentuais. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Define o separador decimal em valores percentuais. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Define o separador de agrupamento em valores percentuais. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Define o número de dígitos por grupo de valor percentual. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Define o padrão negativo de percentagem. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Define o padrão positivo de percentagem. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Define o símbolo de percentagem. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Define o símbolo de permil. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Define o símbolo de infinito positivo. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Define o sinal positivo. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Classe [IFormatProvider](../../system/iformatprovider/)
* Classe [ICloneable](../../system/icloneable/)
* Espaço de nomes [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)