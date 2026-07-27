---
title: StringFormat
second_title: Referência da API Aspose.Slides para C++
description: "Encapsula informações de layout de texto, manipulações de exibição e recursos OpenType. Objetos desta classe devem ser alocados somente usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 313
url: /pt/system.drawing/stringformat/
---
## StringFormat classe

Encapsula informações de layout de texto, manipulações de exibição e recursos OpenType. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class StringFormat : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [Clone](./clone/)() | Retorna uma cópia exata do objeto atual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [StringAlignment](../stringalignment/) [get_Alignment](./get_alignment/)() const | Retorna um valor que indica o alinhamento horizontal da string. |
| **int32_t** [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Retorna um valor que indica o idioma usado quando dígitos locais são substituídos por dígitos ocidentais. |
| [StringDigitSubstitute](../stringdigitsubstitute/) [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Retorna o método de substituição de dígitos. |
| [StringFormatFlags](../stringformatflags/) [get_FormatFlags](./get_formatflags/)() const | Retorna uma combinação bit a bit de StringFormatFlags que especifica o formato de string representado pelo objeto atual. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericDefault](./get_genericdefault/)() | Retorna um objeto [StringFormat](./) que representa um formato padrão genérico. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericTypographic](./get_generictypographic/)() | Retorna um objeto [StringFormat](./) que representa um formato tipográfico genérico. |
| [Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/) [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Retorna o valor que indica como o prefixo de tecla de atalho é exibido. |
| [StringAlignment](../stringalignment/) [get_LineAlignment](./get_linealignment/)() const | Retorna um valor que indica o alinhamento vertical da string. |
| [StringTrimming](../stringtrimming/) [get_Trimming](./get_trimming/)() const | Retorna um valor que indica como a string é truncada. |
| int [GetCharacterRangesCount](./getcharacterrangescount/)() const | Obtém o tamanho da matriz [CharacterRange](../characterrange/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| [ArrayPtr](../../system/arrayptr/)\<**float**\> [GetTabStops](./gettabstops/)(**float**\&) const | Retorna as tabulações para o objeto [StringFormat](./) atual. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Alignment](./set_alignment/)([StringAlignment](../stringalignment/)) | Define o alinhamento horizontal da string. |
| void [set_FormatFlags](./set_formatflags/)([StringFormatFlags](../stringformatflags/)) | Define as bandeiras de formato da string. |
| void [set_HotkeyPrefix](./set_hotkeyprefix/)([Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/)) | Define o valor que especifica como o prefixo de tecla de atalho deve ser exibido. |
| void [set_LineAlignment](./set_linealignment/)([StringAlignment](../stringalignment/)) | Define o alinhamento vertical da string. |
| void [set_Trimming](./set_trimming/)([StringTrimming](../stringtrimming/)) | Define um valor que especifica como a string é truncada. |
| void [SetDigitSubstitution](./setdigitsubstitution/)(**int32_t**, [StringDigitSubstitute](../stringdigitsubstitute/)) | Define o idioma e o método de substituição de dígitos. |
| void [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const [ArrayPtr](../../system/arrayptr/)\<[CharacterRange](../characterrange/)\>\&) | Define um array de objetos [CharacterRange](../characterrange/) que representam os intervalos de caracteres medidos por uma chamada ao método MeasureCharacterRanges(). |
| void [SetTabStops](./settabstops/)(**float**, const [ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Define as tabulações para o objeto [StringFormat](./) atual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
|  [StringFormat](./stringformat/)() | Constrói uma nova instância da classe [StringFormat](./). |
|  [StringFormat](./stringformat/)([StringFormatFlags](../stringformatflags/), **int32_t**) | Constrói uma nova instância da classe [StringFormat](./) com as bandeiras de formato e idioma especificados. |
|  [StringFormat](./stringformat/)(const [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\>\&) | Construtor de cópia. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção typeof([System.Object](../../system/object/)) do C#. |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)